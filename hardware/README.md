# Assembly

[Link to the accompanying paper](https://openhardware.metajnl.com/articles/10.5334/joh.41/)

Taking notes as I go about putting this together.

## Get the parts

### Links to electronic parts

Based on datasheets in the `/hardware/datasheets` folder and the bill of materials

#### Digikey

- [12V power supply](https://www.digikey.com/en/products/detail/tensility-international-corp/16-00143/10324430)
- [Panel Mount HDMI](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4054/9997693)
- [Panel Mount USB-C cable](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4261/10287031)
- [Barrel Jack](https://www.digikey.com/en/products/detail/tensility-international-corp/10-02879/8635386)
- [power rocker switch](https://www.digikey.com/en/products/detail/e-switch/RA41G31900/8540802)
- [2 pin screw terminal (x2)](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/691214110002S/11477397)
- [3 pin screw terminal](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/691214110003S/11477432)
- [capacitor](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/860240572001/5729254)
- [resistor](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT10K0/1741265)
- [40 pin header](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC202LFBN-RC/807240)
- [stepper motor header](https://www.digikey.com/en/products/detail/harwin-inc/M20-9750446/3727931)
- [A4988 female pins](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPTC081LFBN-RC/810147)

#### Amazon

- Raspberry pi 4 is very hard to come by presently so going to try this with a [pico](https://www.amazon.com/gp/product/B0BJ1PGZCX/ref=sw_img_1?smid=AV3WCPW70PEXC&th=1)
  - maybe dont need [Raspberry Pi power supply](https://www.sparkfun.com/products/15448)
- stepper motor in BOM is not available, trying [this one](https://www.amazon.com/STEPPERONLINE-Stepper-Bipolar-Connector-compatible/dp/B00PNEQKC0/ref=pd_bxgy_sccl_1/144-2898604-9241332?pd_rd_w=YvrXU&content-id=amzn1.sym.7f0cf323-50c6-49e3-b3f9-63546bb79c92&pf_rd_p=7f0cf323-50c6-49e3-b3f9-63546bb79c92&pf_rd_r=G23MH1AF0BBMRATTH35H&pd_rd_wg=6DRrk&pd_rd_r=56f43b30-c1b5-4bd5-80b3-f7023c841a44&pd_rd_i=B00PNEQKC0&psc=1)
- Plastic cover for treats - Link broken
- [zip ties](https://www.amazon.com/gp/product/B08F77YVYB/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&th=1)

#### adafruit

- [IR beam break sensor](https://www.adafruit.com/product/2167)

### PCB board

Go to [JLCPCB](https://cart.jlcpcb.com/quote) and upload the [gerber files zip](https://github.com/unl-cchil/canine_precise_dispenser/blob/911b93b65d88298c4af2cbdf4fc43f9101a7e7d7/hardware/pi_hat/gerbers/DispenserV2.0_2021-07-17.zip) from the `/hardware/pi_hat/gerbers` folder.

### Dispenser parts

Get quote at [craftcloud](https://craftcloud3d.com/?utm_campaign=navbar1&utm_source=all3dp&utm_term=buyer%27s+guides&utm_medium=article&utm_content=https%3A%2F%2Fall3dp.com%2F1%2Fbest-online-3d-printing-service-3d-print-services%2F) for .stl files in `/hardware/dispenser/stls` folder.
