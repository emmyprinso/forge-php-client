# JobPayloadInput

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**urn** | **string** | The design URN; returned when uploading the file to Forge The URN needs to be [Base64 (URL Safe) encoded](https://developer.autodesk.com/en/docs/model-derivative/v2/reference/http/job-POST/#id3). | 
**compressed_urn** | **bool** | Set this to &#x60;true&#x60; if the source file is compressed. If set to &#x60;true&#x60;, you need to define the &#x60;rootFilename&#x60;. | [optional] [default to false]
**root_filename** | **string** | The root filename of the compressed file. Mandatory if the &#x60;compressedUrn&#x60; is set to &#x60;true&#x60;. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


