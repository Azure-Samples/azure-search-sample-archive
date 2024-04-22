# Azure Cognitive Search sample archive

This repository contains code samples for Azure Cognitive Search that are no longer supported. This archive exists for samples that originated in repositories that are still active.

Documentation for archived samples can be found at [Cognitive Search documentation archive](https://learn.microsoft.com/previous-versions/azure/search/).

## In this archive

| Sample | Archive date | Description |
|--------|--------------|-------------|
| DotNetHowToSynonyms | April 2024 | This C# sample was used to demonstrate the benefits of adding a synonym map using "before-and-after" queries. The Azure SDK team provides a more recent sample. See [Azure.Search.Documents Samples - Service Operations](https://github.com/Azure/azure-sdk-for-net/blob/main/sdk/search/Azure.Search.Documents/samples/Sample02_Service.md#create-a-synonym-map) for replacement code. |
| DotNetHowToSecurityTrimming | October 2023 | This C# sample was used to demonstrate row-level access on search documents through security filters that include or exclude search results based on a user ID. It was originally in the [search-dotnet-getting-started](https://github.com/Azure-Samples/search-dotnet-getting-started) GitHub repo. It's replaced by code in the [azure-search-openai-demo](https://github.com/Azure-Samples/azure-search-openai-demo) repository. See [this blog post](https://techcommunity.microsoft.com/t5/ai-azure-ai-services-blog/access-control-in-generative-ai-applications-with-azure/ba-p/3956408) for an overview. |
| image-processing | July 2023 | This sample is a Jupyter Python3 .ipynb file that is no longer maintained. It showed how to work with image skills in a skillset, such as Optical Character Recognition (OCR) and redaction of personally identifying information, but the sample's purpose was to demonstrate the coordination of image file handoffs from one skill to the next. |
| create-first-app | March 2023 | "Create your first search app in C#" was a series of tutorials and code samples written for ASP.NET Core 3.1 and MVC. Lessons cover creating a basic search page, pagination, autocomplete and suggestions, faceted navigation, and sorting. It's replaced by an [updated MVC code sample](https://github.com/Azure-Samples/azure-search-dotnet-samples/tree/main/create-mvc-app) that demonstrates server-side operations for filtering and sorting. For client interaction, such as paging through results or facet navigation, see [this sample built on a React template](https://github.com/azure-samples/azure-search-dotnet-samples/tree/main/search-website-functions-v4). |
