# TuringPI-Cluster
Discussions and actions taken to create a TuringPi 2 Cluster

## Purpose

To provide insight into the steps and planning required to put together a TuringPi Cluser.  This cluster will be used for HOMELAB experiments and handling database and presentation layers.

----

## Planned Hardware and Pricing.

Since this is 2024 and the best TuringPI option is version 2 of the [TuringPI](https://docs.turingpi.com/docs/turing-pi2-intro)[^1].  This setup will allow for upto 4 expansion slots which can contain a wide variety of processing cards that are all linked together internally via a 1 gbs enternet connection.  These modules can be any mix of CM4 (with apadter boards), Jetson Nano/Orion (AI processors), and the new RK1 3588 Rockchip. This should provide ampule processing power for a reallt nice homelab.

Case will be one of the following choices:
*  [Thermaltake Tower 200 Mini-ITX](https://www.amazon.com/dp/B0CQ32LMQF/?coliid=I3ENRBT38RE58T&colid=BTFFRD46RDAH&psc=1&ref_=list_c_wl_lv_ov_lig_dp_it)
!(/img/ThermaltakeTower200.jpg "Title")
*  [NZXT H210i - CA-H210i-BR](https://www.amazon.com/gp/product/B07T7L74D5/ref=ox_sc_saved_title_6?smid=&psc=1)
![alt text](/path/img.jpg "Title")

----

## Testing

* ### Testing Main board

* ### Testing CM4 with SD Card

* ### Testing RK1 16GB eMMC flashing
  * #### Confirming usb and serial console
  * #### Flashing Unbuntu 22.04

----

## Assyembling the case



----

## Choosing the initial software K0s v k3s v k8s

* **k0s**
* **k3s**
* **k8s**


----

## What applications are to run on the cluster

* Some Database
  * MySql
  * NoSql
  * postgresql
  * others?
* Grafana for reporting
* Custom application for data collection

----

## References

[^1]: [TuringPI](https://docs.turingpi.com/docs/turing-pi2-intro)

