

# XDI

**XDI** (XRI Data Interchange) is a generalized, extensible service for sharing, linking, and synchronizing structured data over the Internet and other data networks using XRI-addressable [RDF](http://en.wikipedia.org/wiki/Resource_Description_Framework "Resource Description Framework") graphs. XDI is under development by the [OASIS](http://en.wikipedia.org/wiki/OASIS_(organization) "OASIS (organization)") [XDI Technical Committee](http://www.oasis-open.org/committees/xdi).

The main features of XDI are: the ability to link and nest RDF graphs to provide context; full addressability of all nodes in the graph at any level of context; representation of XDI operations as graph statements so authorization can be built into the graph (a feature called XDI link contracts); standard serialization formats including JSON and XML; and a simple ontology language for defining shared semantics using XDI dictionary services.

XDI graphs can be serialized in a number of formats, including [XML](http://en.wikipedia.org/wiki/XML "XML") and [JSON](http://en.wikipedia.org/wiki/JSON "JSON"). Since XDI documents are already fully structured, XML adds very little value, so JSON is the preferred serialization format. The XDI protocol can be bound to multiple transport protocols. The XDI TC is defining bindings to [HTTP](http://en.wikipedia.org/wiki/HTTP "HTTP") and [HTTPS](http://en.wikipedia.org/wiki/HTTPS "HTTPS"), however it is also exploring bindings to [XMPP](http://en.wikipedia.org/wiki/XMPP "XMPP") and potentially directly to [TCP/IP](http://en.wikipedia.org/wiki/TCP/IP "TCP/IP").

XDI provides a standardized portable authorization format call XDI [link contracts](http://en.wikipedia.org/wiki/Link_contract "Link contract"). Link contracts are themselves XDI documents (which may be contained in other XDI documents) that enable control over the authority, security, privacy, and rights of shared data to be expressed in a standard machine-readable format and understood by any XDI endpoint.

This approach to a globally distributed data sharing network models the real-world mechanism of [social contracts](http://en.wikipedia.org/wiki/Social_contract "Social contract") and legal contracts that bind civilized people and organizations in the real world today. Thus XDI can be a key enabler of the [Social Web](http://en.wikipedia.org/wiki/Social_Web "Social Web"). It has also been cited as a mechanism to support a new legal concept, [Virtual Rights](http://www.virtualrights.org), which are based on a new legal entity, the "virtual identity", and a new fundamental right: "to have or not to have a virtual identity".

Public services based on the OASIS [XRI](http://www.oasis-open.org/committees/xri) and [XDI](http://www.oasis-open.org/committees/xdi) specifications are under development by an international non-profit organization, [XDI.ORG](http://www.xdi.org).

## See also

- [XRI](http://en.wikipedia.org/wiki/XRI "XRI")
- [XRDS](http://en.wikipedia.org/wiki/XRDS "XRDS")
- [link contract](http://en.wikipedia.org/wiki/Link_contract "Link contract")
- [i-name](http://en.wikipedia.org/wiki/I-name "I-name")
- [i-number](http://en.wikipedia.org/wiki/I-number "I-number")
- [i-broker](http://en.wikipedia.org/wiki/I-broker "I-broker")
- [Social Web](http://en.wikipedia.org/wiki/Social_Web "Social Web")
- [OpenID](http://en.wikipedia.org/wiki/OpenID "OpenID")
- [Higgins project](http://en.wikipedia.org/wiki/Higgins_project "Higgins project")

## External links

- [OASIS XDI TC wiki page with links to documents explaining the XDI graph model](http://wiki.oasis-open.org/xdi/XdiGraphModel)
- [JSON serialization format](https://wiki.oasis-open.org/xdi/JSONSerializationRules)
- [OASIS XDI Technical Committee](http://www.oasis-open.org/committees/xdi)
- [OASIS XRI Technical Committee](http://www.oasis-open.org/committees/xri)
- [XDI.ORG](http://www.xdi.org)
- [The Social Web: Creating An Open Social Network with XDI](http://journal.planetwork.net/article.php?lab=reed0704) in the [Planetwork Journal](http://journal.planetwork.net).
- [Virtual Rights](http://www.virtualrights.org)

### Implementations

- [XDI reference implementation in Java](http://wiki.eclipse.org/XDI4j) (includes a number of utilities for experimenting directly with XDI, although in older serialization formats)

## Navigation menu

* * *
This page was forked with permission from [http://en.wikipedia.org/wiki/XDI](http://en.wikipedia.org/wiki/XDI)
* * *
