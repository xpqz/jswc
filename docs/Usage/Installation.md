# Installation                                     
 
 EWC is developed as an open-sourcen GitHub repository. To download the code, you can either install Git and clone the repository using the following command:

 `git clone https://github.com/dyalog/ewc.git`

 Alternatively, you can just download a [zip file](https://github.com/dyalog/ewc/archive/refs/heads/main.zip) containing all the code.

## Verify Installation

The simplest way to verify installtion is to run the demo application:

`]link.create # /path/to/ewc`
`demo.Run ''`

This will pop up a form with a Dyalog logo and a dropdown on the right which allows
you to select a variety of simple test applications that have been used to test
EWC during development.

Alternatively, after linking ewc, you can create a form as follows:

`EWC.Init 'Desktop'`
`'F1' eWC 'Form' 'Hello World' (10 10) (400 600)`

This should create an HTMLRenderer window with the caption "Hello World". For more
information on getting started, see [initialisation](Usage/Initialisation.md).

## EWC Development

If you are developing EWC, or you are working with EWC developers and need to
quickly pick up changes to the JavaScript client, it may be a good idea to clone
the client code separately. In order for EWC to automatically find this code,
it must be located in a folder called ewc-client, in the same folder as EWC itself.

You can achieve this using:

 `git clone https://github.com/dyalog/ewc-client.git`