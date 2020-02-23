# Blue Prism Syslog Message Example

A Blue Prism Release Package containing an example Visual Business Object (VBO) and Process to demonstrate sending messages to a Syslog Server using the open source SyslogNet client library for .NET.

The Release Package was created with Blue Prism 6.4.

### Getting Started

In order to send messages to Syslog, you must have a Syslog Server setup and configured. You will need its IP address and UDP Port number to send messages.

### Installing

Download the [Example Blue Prism Package](ShmoopySoftBluePrismSyslogMessageExample.bprelease)

1. Launch Blue Prism
2. Click File -> Import
3. Select the 'ShmoopySoftBluePrismSyslogMessageExample.bprelease' Release Package
4. Follow the Blue Prism import wizard to install the package

### Running

1. In Process Studio, open the process named 'Syslog Process'
2. Edit the 'vProcId' and 'vMsgId' data items if sending an Rfc 5424 message
3. Edit the 'colStructuredDataElements' collection is sending an Rfc 5424 message
3. Edit the 'vMessageText' data item to set the message text you want to send (both Rfc 3164 and Rfc 5424)
4. Click the Run button, or press F5

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* https://github.com/emertechie/SyslogNet
