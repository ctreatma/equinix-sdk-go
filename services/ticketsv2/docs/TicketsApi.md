# \TicketsApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddNotesToTicket**](TicketsApi.md#AddNotesToTicket) | **Post** /v2/tickets/{id}/notes | Add notes to ticket
[**CancelATicket**](TicketsApi.md#CancelATicket) | **Post** /v2/tickets/{id}/cancel | Cancel a ticket
[**CreateATicket**](TicketsApi.md#CreateATicket) | **Post** /v2/tickets | Create a Ticket
[**RetrieveATicket**](TicketsApi.md#RetrieveATicket) | **Get** /v2/tickets/{id} | Retrieve a ticket
[**UpdateATicket**](TicketsApi.md#UpdateATicket) | **Patch** /v2/tickets/{id} | Update a Ticket



## AddNotesToTicket

> AddNotesToTicket(ctx, id).NoteRequest(noteRequest).Execute()

Add notes to ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/ticketsv2"
)

func main() {
	id := "id_example" // string | Identifier of the ticket
	noteRequest := *openapiclient.NewNoteRequest("More details to the ticket") // NoteRequest | Add a note

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TicketsApi.AddNotesToTicket(context.Background(), id).NoteRequest(noteRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketsApi.AddNotesToTicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Identifier of the ticket | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddNotesToTicketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **noteRequest** | [**NoteRequest**](NoteRequest.md) | Add a note | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelATicket

> CancelATicket(ctx, id).TicketsCancel(ticketsCancel).Execute()

Cancel a ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/ticketsv2"
)

func main() {
	id := "id_example" // string | Identifier of the ticket.
	ticketsCancel := *openapiclient.NewTicketsCancel("Duplicate ticket was raised, and issue was already resolved. Refer to ticket id 1-100000000000.") // TicketsCancel | The ticket to be cancelled.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TicketsApi.CancelATicket(context.Background(), id).TicketsCancel(ticketsCancel).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketsApi.CancelATicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Identifier of the ticket. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelATicketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ticketsCancel** | [**TicketsCancel**](TicketsCancel.md) | The ticket to be cancelled. | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateATicket

> CreateATicket(ctx).TicketsCreate(ticketsCreate).Execute()

Create a Ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/equinix/equinix-sdk-go/services/ticketsv2"
)

func main() {
	ticketsCreate := *openapiclient.NewTicketsCreate(openapiclient.Tickets_Create_code("0000-0000"), "Description of the trouble or issue", "AM0:000:00000", time.Now()) // TicketsCreate |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TicketsApi.CreateATicket(context.Background()).TicketsCreate(ticketsCreate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketsApi.CreateATicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateATicketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticketsCreate** | [**TicketsCreate**](TicketsCreate.md) |  | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrieveATicket

> Tickets RetrieveATicket(ctx, id).Execute()

Retrieve a ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/ticketsv2"
)

func main() {
	id := "id_example" // string | Identifier of the ticket.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TicketsApi.RetrieveATicket(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketsApi.RetrieveATicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveATicket`: Tickets
	fmt.Fprintf(os.Stdout, "Response from `TicketsApi.RetrieveATicket`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Identifier of the ticket. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveATicketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Tickets**](Tickets.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateATicket

> UpdateATicket(ctx, id).TicketsModify(ticketsModify).Execute()

Update a Ticket



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/ticketsv2"
)

func main() {
	id := "id_example" // string | Identifier of the ticket.
	ticketsModify := *openapiclient.NewTicketsModify([]openapiclient.ContactRequestRegisteredUserUpdate{*openapiclient.NewContactRequestRegisteredUserUpdate([]string{"username@mail.com"}, openapiclient.ContactRequestRegisteredUser_Update_type("NOTIFICATION"))}) // TicketsModify | The ticket to be updated

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TicketsApi.UpdateATicket(context.Background(), id).TicketsModify(ticketsModify).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TicketsApi.UpdateATicket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Identifier of the ticket. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateATicketRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ticketsModify** | [**TicketsModify**](TicketsModify.md) | The ticket to be updated | 

### Return type

 (empty response body)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

