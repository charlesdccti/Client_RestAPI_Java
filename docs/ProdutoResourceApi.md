# ProdutoResourceApi

All URIs are relative to *https://apirest-springboot.herokuapp.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**atualizaProdutoUsingPUT**](ProdutoResourceApi.md#atualizaProdutoUsingPUT) | **PUT** /api/produto | atualizaProduto
[**deletaProdutoUsingDELETE**](ProdutoResourceApi.md#deletaProdutoUsingDELETE) | **DELETE** /api/produto | deletaProduto
[**listaProdutoUnicoUsingGET**](ProdutoResourceApi.md#listaProdutoUnicoUsingGET) | **GET** /api/produto/{id} | listaProdutoUnico
[**listaProdutosUsingGET**](ProdutoResourceApi.md#listaProdutosUsingGET) | **GET** /api/produtos | listaProdutos
[**salvaProdutoUsingPOST**](ProdutoResourceApi.md#salvaProdutoUsingPOST) | **POST** /api/produto | salvaProduto


<a name="atualizaProdutoUsingPUT"></a>
# **atualizaProdutoUsingPUT**
> Produto atualizaProdutoUsingPUT(produto)

atualizaProduto

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProdutoResourceApi;


ProdutoResourceApi apiInstance = new ProdutoResourceApi();
Produto produto = new Produto(); // Produto | produto
try {
    Produto result = apiInstance.atualizaProdutoUsingPUT(produto);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProdutoResourceApi#atualizaProdutoUsingPUT");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **produto** | [**Produto**](Produto.md)| produto |

### Return type

[**Produto**](Produto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

<a name="deletaProdutoUsingDELETE"></a>
# **deletaProdutoUsingDELETE**
> deletaProdutoUsingDELETE(produto)

deletaProduto

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProdutoResourceApi;


ProdutoResourceApi apiInstance = new ProdutoResourceApi();
Produto produto = new Produto(); // Produto | produto
try {
    apiInstance.deletaProdutoUsingDELETE(produto);
} catch (ApiException e) {
    System.err.println("Exception when calling ProdutoResourceApi#deletaProdutoUsingDELETE");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **produto** | [**Produto**](Produto.md)| produto |

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: */*

<a name="listaProdutoUnicoUsingGET"></a>
# **listaProdutoUnicoUsingGET**
> Produto listaProdutoUnicoUsingGET(id)

listaProdutoUnico

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProdutoResourceApi;


ProdutoResourceApi apiInstance = new ProdutoResourceApi();
Long id = 789L; // Long | id
try {
    Produto result = apiInstance.listaProdutoUnicoUsingGET(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProdutoResourceApi#listaProdutoUnicoUsingGET");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Long**| id |

### Return type

[**Produto**](Produto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="listaProdutosUsingGET"></a>
# **listaProdutosUsingGET**
> List&lt;Produto&gt; listaProdutosUsingGET()

listaProdutos

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProdutoResourceApi;


ProdutoResourceApi apiInstance = new ProdutoResourceApi();
try {
    List<Produto> result = apiInstance.listaProdutosUsingGET();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProdutoResourceApi#listaProdutosUsingGET");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**List&lt;Produto&gt;**](Produto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="salvaProdutoUsingPOST"></a>
# **salvaProdutoUsingPOST**
> Produto salvaProdutoUsingPOST(produto)

salvaProduto

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.ProdutoResourceApi;


ProdutoResourceApi apiInstance = new ProdutoResourceApi();
Produto produto = new Produto(); // Produto | produto
try {
    Produto result = apiInstance.salvaProdutoUsingPOST(produto);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProdutoResourceApi#salvaProdutoUsingPOST");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **produto** | [**Produto**](Produto.md)| produto |

### Return type

[**Produto**](Produto.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

