Dynamic Message Routing in PubSub+ Cloud
=======================================

In PubSub+ Cloud, all enterprise messaging services are created with the Dynamic Message Routing (DMR) feature enabled. To learn more about DMR,
checkout `the official documentation in the Solace Tech Docs <https://docs.solace.com/Features/Dynamic-Msg-Routing.htm>`_.

PubSub+ Cloud will only prepare services for DMR in the following plans:

- Kilo
- Mega
- Giga
- Tera

The message VPN created by PubSub+ Cloud has DMR enabled. A DMR cluster is automatically configured in the message VPN for the service. The password
for cluster communication is stored in PubSub+ Cloud and available from the status tab on the service details page, along with all other relevant DMR cluster
information.

Note that in PubSub+ Cloud, only external links can be created for DMR clusters at this time. To create DMR cluster links, use the 
`click-to-connect feature <https://docs.solace.com/Configuring-and-Managing/DMR-Examples.htm>`_ in the PubSub+ Manager.