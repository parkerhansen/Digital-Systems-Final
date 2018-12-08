## Error Detection

[Back](README.md)

---

<p align="center"><img src="networkError.jpg" height="384" width="512"></p>

---

#### Contents

1. [How do digital networks detect errors?](#how)
2. [Parity Checking](#parity)

<br>

---

## <a name="how"> How do digital networks detect errors?
When sending data over a network there are situations, pretty much all the time, where it is very important that the data received on the other end is complete and identical to information transmitted. Thus digital networks need to have the ability to check if the data being transmitted is received completely. Computers and digital networks thus have all kinds of ways of checking the information they send.

One of the most simple checks is sending the data twice and comparing the data received to see if they are identical, if they aren't then they ask for the data to be re-sent.
