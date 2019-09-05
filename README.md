# ios-sdk-mopub-mediation-adapter

This repository contains adapters for MoPub mediation. 

Refer [integration document](https://publisherdocs.criteotilt.com/sdk-ios/3.1/mopub-mediation/) on how to setUp Custom Events and integrate MoPub for Mediation.

Criteo Direct Bidder can be integrated via the __CriteoPublisherSdk__ framework using the below options.

__Note__: CriteoPublisherSdk framework does not include adapters. The adapter source code will have to be manually copied from this repository and added to your project sources.

## CocoaPods Installation

You can install __CriteoPublisherSdk__ by declaring the pod ```criteopublishersdk``` in your _podfile_ as below

```
pod 'criteopublishersdk'
```

## Manual Installation

You can download the __CriteoPublisherSdk__ framework from [here](https://publisherdocs.criteotilt.com/sdk-ios/3.1/mopub-mediation/). 

You will need to add this framework under __Linked Frameworks and Libraries__ in Build Settings of your app
as mentioned [here](https://publisherdocs.criteotilt.com/sdk-ios/2.2/googleadmanager/#add-criteo-module)
