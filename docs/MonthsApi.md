# YnabApi::MonthsApi

All URIs are relative to *https://api.youneedabudget.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_budget_month**](MonthsApi.md#get_budget_month) | **GET** /budgets/{budget_id}/months/{month} | Single budget month
[**get_budget_months**](MonthsApi.md#get_budget_months) | **GET** /budgets/{budget_id}/months | List budget months


# **get_budget_month**
> MonthDetailResponse get_budget_month(budget_id, month)

Single budget month

Returns a single budget month

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **budget_id** | [**String**](.md)| The ID of the Budget. | 
 **month** | **Date**| The Budget Month.  \&quot;current\&quot; can also be used to specify the current calendar month (UTC). | 

### Return type

[**MonthDetailResponse**](MonthDetailResponse.md)

# **get_budget_months**
> MonthSummariesResponse get_budget_months(budget_id)

List budget months

Returns all budget months

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **budget_id** | [**String**](.md)| The ID of the Budget. | 

### Return type

[**MonthSummariesResponse**](MonthSummariesResponse.md)

