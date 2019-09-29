# LembreteResourceApi

All URIs are relative to *https://apirest-springboot.herokuapp.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**atualizaLembreteUsingPUT**](LembreteResourceApi.md#atualizaLembreteUsingPUT) | **PUT** /api/lembrete/{id} | atualizaLembrete
[**deletaLembreteByIdUsingDELETE**](LembreteResourceApi.md#deletaLembreteByIdUsingDELETE) | **DELETE** /api/lembrete/{id} | deletaLembreteById
[**deletaLembreteUsingDELETE**](LembreteResourceApi.md#deletaLembreteUsingDELETE) | **DELETE** /api/lembrete | deletaLembrete
[**findByIdUsingGET**](LembreteResourceApi.md#findByIdUsingGET) | **GET** /api/lembrete/{id} | findById
[**listaLembretesUsingGET**](LembreteResourceApi.md#listaLembretesUsingGET) | **GET** /api/lembrete | listaLembretes
[**salvaLembreteUsingPOST**](LembreteResourceApi.md#salvaLembreteUsingPOST) | **POST** /api/lembrete | salvaLembrete


<a name="atualizaLembreteUsingPUT"></a>
# **atualizaLembreteUsingPUT**
> Lembrete atualizaLembreteUsingPUT(lembrete, id)

atualizaLembrete

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
Lembrete lembrete = new Lembrete(); // Lembrete | lembrete
Long id = 789L; // Long | id
try {
    Lembrete result = apiInstance.atualizaLembreteUsingPUT(lembrete, id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#atualizaLembreteUsingPUT");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lembrete** | [**Lembrete**](Lembrete.md)| lembrete |
 **id** | **Long**| id |

### Return type

[**Lembrete**](Lembrete.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

<a name="deletaLembreteByIdUsingDELETE"></a>
# **deletaLembreteByIdUsingDELETE**
> deletaLembreteByIdUsingDELETE(id)

deletaLembreteById

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
Long id = 789L; // Long | id
try {
    apiInstance.deletaLembreteByIdUsingDELETE(id);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#deletaLembreteByIdUsingDELETE");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

<a name="deletaLembreteUsingDELETE"></a>
# **deletaLembreteUsingDELETE**
> deletaLembreteUsingDELETE(lembrete)

deletaLembrete

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
Lembrete lembrete = new Lembrete(); // Lembrete | lembrete
try {
    apiInstance.deletaLembreteUsingDELETE(lembrete);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#deletaLembreteUsingDELETE");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lembrete** | [**Lembrete**](Lembrete.md)| lembrete |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

<a name="findByIdUsingGET"></a>
# **findByIdUsingGET**
> Lembrete findByIdUsingGET(id)

findById

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
Long id = 789L; // Long | id
try {
    Lembrete result = apiInstance.findByIdUsingGET(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#findByIdUsingGET");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id |

### Return type

[**Lembrete**](Lembrete.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="listaLembretesUsingGET"></a>
# **listaLembretesUsingGET**
> List&lt;Lembrete&gt; listaLembretesUsingGET()

listaLembretes

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
try {
    List<Lembrete> result = apiInstance.listaLembretesUsingGET();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#listaLembretesUsingGET");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List&lt;Lembrete&gt;**](Lembrete.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="salvaLembreteUsingPOST"></a>
# **salvaLembreteUsingPOST**
> Lembrete salvaLembreteUsingPOST(lembrete)

salvaLembrete

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.LembreteResourceApi;


LembreteResourceApi apiInstance = new LembreteResourceApi();
Lembrete lembrete = new Lembrete(); // Lembrete | lembrete
try {
    Lembrete result = apiInstance.salvaLembreteUsingPOST(lembrete);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling LembreteResourceApi#salvaLembreteUsingPOST");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **lembrete** | [**Lembrete**](Lembrete.md)| lembrete |

### Return type

[**Lembrete**](Lembrete.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

