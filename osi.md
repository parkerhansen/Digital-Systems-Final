## The Open Systems Interconnection (OSI) Model

[Back](README.md)

---

<p align="center"><img src="https://images.idgesg.net/images/article/2017/12/osimodel-100743439-large.jpg" height="384" width="512"></p>

---

#### Contents

1. [OSI Model](#osi)
    <br> [Layers](#layers):
    <br>- [Physical](#physical)
    <br>- [Data Link](#data)
    <br>- [Network](#network)
    <br>- [Transport](#transport)
    <br>- [Session](#session)
    <br>- [Presentation](#presentation)
    <br>- [Application](#application)

<br>

---

## <a name="osi"> What is the OSI Model?
The Open Systems Interconnection (OSI) Model is a way of describing a computer network as a stack of seven layers. The lowest layers have more application to the computer hardware while the higher layers are related more to the end user. As you progress through the layers you realize that the lower layers allow for the higher layers to occur.

---

## <a name="layers"> The Layers

### <a name="physical"> [Physical Layer](https://en.wikipedia.org/wiki/Physical_layer)
The physical layer is the first and lowest layer contains all the hardware necessary to connect devices to the network. It defines a means and allows for the transmission of data but does not have to do with the actual act of transmitting data.

### <a name="data"> [Data Link Layer](https://en.wikipedia.org/wiki/Data_link_layer)
The next layer is the data link layer which provides the functional and procedural means to transfer data between devices on the network. This layer also provides the ability to detect and possibly correct errors that have occurred.

### <a name="network"> [Network Layer](https://en.wikipedia.org/wiki/Network_layer)
This layer is responsible for how data is addressed and routed from one device to another.

### <a name="transport"> [Transport Layer](https://en.wikipedia.org/wiki/Transport_layer)
When moving into the transport layer data is finally able to be moved reliably and efficiency across the network, ensuring the transmission is complete.

### <a name="session"> [Session Layer](https://en.wikipedia.org/wiki/Session_layer)
The session layer allows and controls the temporary sessions of the network, allowing them to be opened, closed, and managed. These sessions allow for communication on the network and thus data/information to be exchanged.

### <a name="presentation"> [Presentation Layer](https://en.wikipedia.org/wiki/Presentation_layer)
The presentation layer is responsible for the how the data/information is delivered and formatted so it can be further processed or eventually displayed. Some examples this layer can do is compression(reducing the size of the information that need to be transported), encryption, or conversion of data to be readable.

### <a name="application"> [Applicaiton Layer](https://en.wikipedia.org/wiki/Application_layer)
The last, highest, and closest to the end user layer is the application layer. It contains the interface that the end user interacts with. It is the user interface and is responsible for displaying received information to the user.

---
