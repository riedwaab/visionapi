# visionapi
Azure Vision API Test build
This is a test build of the Azure Vision API. It analyses all JPG files in a partiular directory. The output is displayed on screen and the JSON is written to a .json file with the name name as the image.

## Requirements
You will need to deploy Azure Vision API and create an appconfig.json file. In this fule, you will store your API settings like this:
```json
{
    "APIEndpoint": "https://westeurope.api.cognitive.microsoft.com/vision/v1.0",
    "APIKey": "1139e3309d7b471597aa00e1bf77afce"
}
```
So replace the above with your own API endpoint, and API Key.

## References
 - [Azure Computer Vision Overview](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/)
 - [Computer Vision C# Quick Starts](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/quickstarts/csharp)
