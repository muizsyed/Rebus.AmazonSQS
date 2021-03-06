# Changelog

## 2.0.0-a1

* Test release

## 2.0.0-a4

* Test release again

## 2.0.0-b01

* Test release

## 2.0.0-b02

* More convenient namespaces

## 2.0.0

* Update AWS Core and SQS deps to 3.3.0
* Release 2.0.0

## 2.1.0

* Add configuration extension that accepts `AWSCredentials` - thanks [MooseMagnet]

## 3.0.0

* Update to Rebus 3

## 4.0.0

* Update to Rebus 4
* Add .NET Core support (netstandard 1.3)
* Change message format to break out of SQS's limitation of being able to transfer only 10 headers - thanks [mvandevy]
* Fix csproj - thanks [robvanpamel]
* Add ability to use an external timeout manager or Rebus' ordinary timeout managers to overcome SQS limitations
* Add ability to skip queue creation - thanks [robvanpamel]
* Remember to configure visibility timeout for queues created by Rebus - thanks [micdah]

---

[micdah]: https://github.com/micdah
[MooseMagnet]: https://github.com/MooseMagnet
[mvandevy]: https://github.com/mvandevy
[robvanpamel]: https://github.com/robvanpamel

