# \SmartHandsSupportPlansApi

All URIs are relative to *https://api.equinix.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RetrieveSmartHandsSupportPlans**](SmartHandsSupportPlansApi.md#RetrieveSmartHandsSupportPlans) | **Get** /colocations/v2/supportPlans | Retrieve Smart Hands support plans



## RetrieveSmartHandsSupportPlans

> SupportPlanResponse RetrieveSmartHandsSupportPlans(ctx).AccountNumbers(accountNumbers).Ibxs(ibxs).Offset(offset).Limit(limit).Sorts(sorts).PlanIds(planIds).Execute()

Retrieve Smart Hands support plans



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/equinix/equinix-sdk-go/services/supportplansv2"
)

func main() {
	accountNumbers := []string{"Inner_example"} // []string | List of accounts to be filtered (optional)
	ibxs := []string{"Inner_example"} // []string | List of IBXs to be filtered (optional)
	offset := int32(56) // int32 | Use `offset` to control the number of records to be skipped in the response. (optional) (default to 0)
	limit := int32(56) // int32 | Use `limit` to restrict the number of records in the response. (optional) (default to 10)
	sorts := []openapiclient.RetrieveSmartHandsSupportPlansSortsParameterInner{openapiclient.Retrieve_Smart_Hands_support_plans_sorts_parameter_inner("START_DATE")} // []RetrieveSmartHandsSupportPlansSortsParameterInner | Sort the users in the response in a particular order. For descending order, prefix the field name with '-'. (optional)
	planIds := []string{"Inner_example"} // []string | List of PlanIds to be filtered (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SmartHandsSupportPlansApi.RetrieveSmartHandsSupportPlans(context.Background()).AccountNumbers(accountNumbers).Ibxs(ibxs).Offset(offset).Limit(limit).Sorts(sorts).PlanIds(planIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SmartHandsSupportPlansApi.RetrieveSmartHandsSupportPlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveSmartHandsSupportPlans`: SupportPlanResponse
	fmt.Fprintf(os.Stdout, "Response from `SmartHandsSupportPlansApi.RetrieveSmartHandsSupportPlans`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveSmartHandsSupportPlansRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **accountNumbers** | **[]string** | List of accounts to be filtered | 
 **ibxs** | **[]string** | List of IBXs to be filtered | 
 **offset** | **int32** | Use &#x60;offset&#x60; to control the number of records to be skipped in the response. | [default to 0]
 **limit** | **int32** | Use &#x60;limit&#x60; to restrict the number of records in the response. | [default to 10]
 **sorts** | [**[]RetrieveSmartHandsSupportPlansSortsParameterInner**](RetrieveSmartHandsSupportPlansSortsParameterInner.md) | Sort the users in the response in a particular order. For descending order, prefix the field name with &#39;-&#39;. | 
 **planIds** | **[]string** | List of PlanIds to be filtered | 

### Return type

[**SupportPlanResponse**](SupportPlanResponse.md)

### Authorization

[BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

