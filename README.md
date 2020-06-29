# SuperOffice-PHP7-Sample
User friendly PHP 7 and Netserver 87 compatible PHP Sample application

Thanks to [Dennis Aagaard Mortensgaard](https://github.com/dennis2848) for modernizing and publish this latest sample! Check out his contributions on [SuperOffice Community](https://community.superoffice.com/en/My-Page/11648/).

## Background

This application was built on the original php sample application that was available on the community.

The background for creating this sample application, was to update the old PHP sample to support the new OAuth authentication flow, and the new services made available with newer versions of the NetServer. The foundation is NuSoap, that has been updated to be compatible with PHP Version 7.x. All warnings and errors have been corrected too, and the newest Wsdl files for the newest version of the NetServer has been added as well.

Please feel free to contribute with finishing the agent classes, and making helper classes, so this can stay alive and evolve over time.

## Setup

1. clone the repository
2. register an app @SuperOffice
3. wait for SuperOffice to send you your app id, app token and private certificate
4. convert the private certificate xml into a pem file - you can [do that here](devnet-tokens.azurewebsites.net).
5. put the contents of the generated PEM into the certificates/private.pem file
6. alter the settings.php file
7. upload to a php server (or run it locally)
8. browse to 'https://<<your_url>>/index.php' and start the sample app.

## Practical use cases

This sample application is packaged so that it can be used as a general library written in PHP to communicate with all SuperOffice webservices - therefore the part of the old package that was actually the sample application has been moved into its own subfolder, so the other libraries and helper files can be used by an "external" app structure.

## Further documentation

Please refer to the original documentation on the SuperOffice community:

* [SOAP Documentation](https://community.superoffice.com/documentation/sdk/SO.NetServer.Web.Services/html/Reference-SOAP-SOAP.htm)
* [Application description](https://community.superoffice.com/da/developer/create-apps/samples/minimal-php-app/)