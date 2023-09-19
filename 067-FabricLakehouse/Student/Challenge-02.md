# Challenge 02 - Land ho!

[< Previous Challenge](./Challenge-01.md) - **[Home](../README.md)** - [Next Challenge >](./Challenge-03.md)

## Introduction

Now you've found your data sources, it's time to land your data in OneLake.

## Description

In this challenge you will develop a solution to land your raw data in OneLake. You will need to consider how you will retrieve your data and where you will store in OneLake.

## Success Criteria

To complete this challenge successfully, you should be able to:

- Provisioned any Fabric resources required to land your data
- Demonstrate that each dataset can retrieved automatically (but not necessarily on a schedule)
- Data is stored as-is in raw format in OneLake following a naming convention/location of your choice
- Error handling is always good, but not required for this challenge

## Learning Resources

- What is [OneLake](https://learn.microsoft.com/en-us/fabric/onelake/onelake-overview)?
- Fabric has dozens of connectors eg.
  [HTTP](https://learn.microsoft.com/en-us/fabric/data-factory/connector-http), [REST](https://learn.microsoft.com/en-us/fabric/data-factory/connector-rest-overview) and [OData](https://learn.microsoft.com/en-us/fabric/data-factory/connector-odata-overview)
- Python's [``urllib``](https://docs.python.org/3/library/urllib.html) supports a number of protocols including HTTP and FTP
  
## Tips

- Data providers are often very helpful and may be able to provide you with a code sample if you hunt around their web sites.
- Landing the data automatically is the goal, but you may want to start by manually downloading the data and then work on automating the process. If coding automated retrieval really doesn't float your boat, don't fall overboard, it's fine to manually download the data and then upload it to OneLake.

## Advanced Challenges (Optional)

Too comfortable?  Eager to do more?  Try these additional challenges!

- Schedule your data retrieval
- Archive your raw data before downloading the latest version
- Add some notification logic to alert you on what's going on with your process