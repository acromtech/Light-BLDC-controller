# Light BLDC controller selection

## uDriver v2
<img width="1137" alt="microDriver_v2" src="https://user-images.githubusercontent.com/103576080/168245561-070f91e7-f41c-4bc8-919c-5424a1e39b89.png">

* Weight : 13g
* Dimensions: 51mm x 50mm
* Motor driver : 2
* MCU : [TMS320F2806](https://www.ti.com/lit/ds/symlink/tms320f28069m.pdf?ts=1652431384871&ref_url=https%253A%252F%252Fwww.google.com%252F)
* SPI/CAN
* Input voltage : 5V - 32V
* Open Source : [Github](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware/tree/master/electronics/micro_driver_electronics)

## STorM32 BGC : Board v3.3
![Storm32-bgc-nt-v33-ports-and-connections](http://www.olliw.eu/storm32bgc-wiki/images/thumb/9/90/Storm32-bgc-nt-v33-ports-and-connections.jpg/800px-Storm32-bgc-nt-v33-ports-and-connections.jpg)
* Weight : ?
* Dimensions : 40mm x 25mm
* Motor driver : 0 (need NT or T-STorM32 modules)
* 2 NT ports and one NT-X port
* MCU : [STM32F103RC](https://www.st.com/resource/en/datasheet/cd00191185.pdf) or [STM32F103RE](https://www.st.com/resource/en/datasheet/cd00191185.pdf) at 72 MHz
* 1 CAN, 1 Futaba S-Bus, 4 PWM/Sum-PPM inputs/outputs
* Input voltage : 6-27 V or 2-6S
* [More informations](http://www.olliw.eu/storm32bgc-wiki/STorM32_Boards)
* Open Source : [Github](https://github.com/olliw42/storm32bgc)

## BaseCam SimpleBGC 32bit
![BaseCam SimpleBGC 32-bit Controller](https://www.basecamelectronics.com/media/SimpleBGCARM_3D.png)
* Weight : 22g
* Motor driver : 3
* 32-bit ARM processor
* Support of a wide range of external control protocols : Futaba, Spektrum, 5x PWM, Sum-PPM, 3 ADC, Serial API 
* Support for two IMU sensors and external IMU for maximum precision : The system works with either one or two IMU sensors. The use of two sensors improves stability and accuracy in the non-encoder version.
* Automatic tuning of PID parameters
* [More informations](https://www.basecamelectronics.com/simplebgc32bit/#specs-tab)
* Order : [BaseCam](https://shop.basecamelectronics.com/product/simplebgc-32bit-regular-i2c-1-imu-set-revision-b/)

## BaseCam SimpleBGC 32bit Tiny Rev.C
![SBGC_Tiny_C_Flat_Top_legend](https://user-images.githubusercontent.com/103576080/168251200-e2367232-5464-4a3e-81d4-96f46053f79d.jpg)

* Weight : ?
* Dimensions : 25×40mmx7mm
* Motor driver : 3 
* Has the same set of interfaces as the full-size SimpleBGC 32-bit
* High-voltage motor drivers are connected directly to the power supply
* [More informations](https://www.basecamelectronics.com/sbgc32tiny_rev_c/#downloads-tab)
* Order : [BaseCam](https://shop.basecamelectronics.com/product/simplebgc-32bit-tiny-i2c-2-imu-set-revision-c/)

## Infineon BLDC SHIELD TLE9879TOBO1
![Screenshot 2022-05-13 at 11-03-30 BLDC Shield with TLE9879QXA40 for Arduino - Infineon-BLDC_shield-UserManual-v01_02-EN pdf](https://user-images.githubusercontent.com/103576080/168250139-465d0ec6-5488-44e1-ad74-b48aaa359b99.png)

* Weight : 48g
* Dimensions : 25×40mmx7mm
* Motor driver : 1
* Implemented motor control algorithms : FOC/BEMF/Hall
* Communication : SPI
* Sensor included : No
* MCU : [TLE9879QXA40](https://www.infineon.com/dgdl/Infineon-TLE9879QXA40-DS-v01_00-EN.pdf?fileId=5546d4625a888733015a89d10a283f20)
* [More informations](https://www.infineon.com/cms/en/product/evaluation-boards/bldc_shield_tle9879/)
* Order : [Mouser](https://www.mouser.fr/ProductDetail/Infineon-Technologies/BLDCSHIELDTLE9879TOBO1?qs=vLWxofP3U2x6GaN8Qrdxcg%3D%3D) | [RS](https://fr.rs-online.com/web/p/modules-de-developpement-pour-la-robotique-la-gestion-d-alimentation-et-les-moteurs/2326799?cm_mmc=FR-PLA-DS3A-_-google-_-CSS_FR_FR_Raspberry_Pi_%26_Arduino_%26_Outils_de_developpement_Whoop-_-(FR:Whoop!)+Modules+de+d%C3%A9veloppement+pour+la+robotique+%26+la+gestion+d%27alimentation+et+les+moteurs-_-2326799&matchtype=&pla-337328255420&gclid=CjwKCAjw682TBhATEiwA9crl30HtDDNe_0iPY7PhOcLKeVtZbHx-bQ3umCEcA0vVpX8sjVS2CWlgZBoCJgQQAvD_BwE&gclsrc=aw.ds) | [Farnell](https://fr.farnell.com/infineon/bldcshieldtle9879tobo1/shield-driver-moteur-bldc/dp/3051942)

## STMicroelectronics STEVAL-PTOOL1V1
![image PF270181 en feature-description-include-personalized-no-cpn-large](https://user-images.githubusercontent.com/103576080/168253108-efde8b8e-38e0-456c-8f5b-31cc6b0f86e5.jpg)

* Weight : ?
* Dimensions : 70mm x 30mm
* Motor driver : 1
* MCU : [STSPIN32F0B](https://www.st.com/resource/en/datasheet/stspin32f0b.pdf)
* Input voltage : 7-45 V or 2S-6S batteries
* UART communication
* Sensor included : No
* Plug-and-play capability through six-step firmware with Hall effect sensor feedback
* Six-steps sensorless control available through dedicated BEMF sensing circuitry and sensorless/sensored Field Oriented Control 
* [More informations](https://www.st.com/en/evaluation-tools/steval-ptool1v1.html)
* Order : [Mouser](https://www.mouser.fr/ProductDetail/STMicroelectronics/STEVAL-PTOOL1V1?qs=DPoM0jnrROWG3v%252BK0gmMPA%3D%3D&gclid=CjwKCAjw682TBhATEiwA9crl3_Uw7ZlsB-z0AtxIs56xzSP8aZObUjN_6on-bGDKqf6zWkh7Gurk_RoC4gEQAvD_BwE) | [Farnell](https://fr.farnell.com/stmicroelectronics/steval-ptool1v1/carte-ref-design-ctrl-moteur-bldc/dp/3585924?gclid=CjwKCAjw682TBhATEiwA9crl3xIJ-ErU63Q-33Lv1daACAj9FcH02DKyjcpQxW7xHf7iSzWFD3VxHxoCP3wQAvD_BwE&mckv=_dc|pcrid|592758738912|plid||kword||match||slid||product|3585924|pgrid|135742588499|ptaid|pla-293946777986|&CMP=KNC-GFR-GEN-SMART-SHOPPING-13-Apr-22-Catch-all-2&gross_price=true) | [RS](https://fr.rs-online.com/web/p/modules-de-developpement-pour-la-robotique-la-gestion-d-alimentation-et-les-moteurs/2102026?cm_mmc=FR-PLA-DS3A-_-google-_-CSS_FR_FR_Raspberry_Pi_%26_Arduino_%26_Outils_de_developpement_Whoop-_-(FR:Whoop!)+Modules+de+d%C3%A9veloppement+pour+la+robotique+%26+la+gestion+d%27alimentation+et+les+moteurs-_-2102026&matchtype=&pla-341190694748&gclid=CjwKCAjw682TBhATEiwA9crl38SQhZahkc67V6Rbi6woXXrtXOXdcHTaBIQO0ukJpoVaP4eCEKyKHRoCVu8QAvD_BwE&gclsrc=aw.ds)

## Maxon EPOS4 Compact 24/1.5 CAN, digital positioning controller, 1.5 A, 10 - 24 VDC
![Produktbild-546714-Detail](https://user-images.githubusercontent.com/103576080/168255938-7dc790e8-14f0-4fa5-ba76-ba2e245c5619.jpg)

* Weight : 58g
* Dimensions : 55.0 x 40.0 x 31.1mm
* Motor driver : 1
* Input voltage : 10-24 VDC
* Communication : CAN (CANopen)
* [More informations](https://www.maxongroup.com/maxon/view/product/control/Positionierung/546714)
* Order : [Maxon](https://www.maxongroup.com/maxon/view/product/control/Positionierung/546714)

## jkirson Stealth Controller
![Driver 0 2](https://user-images.githubusercontent.com/103576080/168256381-17ea764d-5007-4794-a907-376216f56cec.png)

* Weight : ?
* Dimensions : 62 x 50mm
* Motor driver : 1
* MCU : [DRV8316](https://www.ti.com/product/DRV8316?utm_source=google&utm_medium=cpc&utm_campaign=asc-mdbu-null-prodfolderdynamic-cpc-pf-google-wwe&utm_content=prodfolddynamic&ds_k=DYNAMIC+SEARCH+ADS&DCM=yes&gclid=Cj0KCQjwg_iTBhDrARIsAD3Ib5hOlbhjXpEbEakNgZszD478o3PeRwf-k7EDuOW6oAS2j8xnXD1vuDkaAuR2EALw_wcB&gclsrc=aw.ds)
* Communication : UART/CAN
* All-in-one : Magnetic encoder/MCU/Communication interface
* Simple FOC library compatible
* [More informations](https://community.simplefoc.com/t/hand-assembling-a-controller/848)
* Open Source : [Github](https://github.com/jkirsons/stealth-controller)

## jkirson Stealth Controller mini
* Weight : ?
* Dimensions : 50 x 36mm
* Motor driver : 1
* MCU : [DRV8316](https://www.ti.com/product/DRV8316?utm_source=google&utm_medium=cpc&utm_campaign=asc-mdbu-null-prodfolderdynamic-cpc-pf-google-wwe&utm_content=prodfolddynamic&ds_k=DYNAMIC+SEARCH+ADS&DCM=yes&gclid=Cj0KCQjwg_iTBhDrARIsAD3Ib5hOlbhjXpEbEakNgZszD478o3PeRwf-k7EDuOW6oAS2j8xnXD1vuDkaAuR2EALw_wcB&gclsrc=aw.ds)
* Communication : UART/CAN
* All-in-one : Magnetic encoder/MCU/Communication interface
* Simple FOC library compatible
* [More informations](https://community.simplefoc.com/t/drv8316-mini-controller/1021)
* Open Source : [Github](https://github.com/jkirsons/stealth-controller-mini)

## jkirson BLDC Driver
![PCB-Back](https://user-images.githubusercontent.com/103576080/168261296-2cbf79a2-ef2b-4d2d-b083-3c8012b3d1bc.png)
![PCB-Front](https://user-images.githubusercontent.com/103576080/168261297-0ad7face-2f81-4707-9a71-5ae21dc989ed.png)

* Weight : ?
* Dimensions : ?
* Motor driver : 1 ([IFX007T Driver](https://www.infineon.com/dgdl/Infineon-IFX007T-DS-v01_00-EN.pdf?fileId=5546d46265f064ff0166433484070b75))
* MCU : [ESP32-PICO-V3](https://www.espressif.com/sites/default/files/documentation/esp32-pico-v3_datasheet_en.pdf)
* Encoder : [MA702 Encoder](https://www.monolithicpower.com/en/documentview/productdocument/index/version/2/document_type/Datasheet/lang/en/sku/MA702GQ-Z/document_id/3561/)
* Communication : UART/CAN ([SN65HVD230QDR CAN Tranceiver](https://www.ti.com/lit/ds/symlink/sn65hvd230q.pdf))
* All-in-one : Magnetic encoder/MCU/Communication interface
* Simple FOC library compatible
* [More informations](https://community.simplefoc.com/t/my-ifx007t-driver-board/683)
* Open Source : [Github](https://github.com/jkirsons/BLDC-Driver-IFX007T)

## ADI Trinamic TMCM-1640
![2822224-40](https://user-images.githubusercontent.com/103576080/168263852-21de9712-3882-416b-9942-0f237ab27c8c.jpg)
![Screenshot 2022-05-13 at 13-38-57 TMCM-1640 Hardware Manual - TMCM-1640_hardware_manual_V1 06 pdf](https://user-images.githubusercontent.com/103576080/168275753-c34f9bac-771a-4ed6-b182-9c633a2c5042.png)

* Weight : 12g
* Dimensions : 42 x 42 x 15mm
* Motor driver : 1
* MCU : ARM Cortex™-M3
* Input voltage : 12-28.5V
* Communication : RS485
* Sensor included : No
* [More informations](https://www.trinamic.com/products/modules/details/tmcm-1640/)
* Order : [Farnell](https://de.farnell.com/trinamic/tmcm-1640/bldc-motorstrg-treiber-1-achsen/dp/2822224?CMP=GRHB-OCTOPART)

## ADI Trinamic TMCM-1636 24V CANopen
![Screenshot 2022-05-13 at 13-33-32 TMCM-1636 CANopen Firmware Manual - TMCM-1636-CANopen_firmware_manual_fw1 12_rev1 03 pdf](https://user-images.githubusercontent.com/103576080/168275060-e3eec7a2-6f63-41fd-b2ac-01dca1fd7e8e.png)
![Screenshot 2022-05-13 at 13-33-57 TMCM-1636 CANopen Firmware Manual - TMCM-1636-CANopen_firmware_manual_fw1 12_rev1 03 pdf](https://user-images.githubusercontent.com/103576080/168275061-9122ed6f-bb62-456c-9745-620eb49bf2ad.png)

* Weight : 70g
* Dimensions : 45 x 90 x 18mm
* Motor driver : 1
* Input voltage : 12-18V
* Communication : CANopen/UART
* Sensor included : No
* Feedback options : 2 incremental quadrature encoders, digital HALL sensor, absolute SPI- and SSI-based encoders
* [More informations](https://www.trinamic.com/products/modules/details/tmcm-1636/)
* Order : [Farnell](https://de.farnell.com/trinamic/tmcm-1636-24v-canopen/schrittmotor-canopen-12-28v-dc/dp/3515657?CMP=GRHB-OCTOPART)

## mjbots moteus r4.8 controller
![Screenshot 2022-05-13 at 13-31-52 moteus r4 11 controller](https://user-images.githubusercontent.com/103576080/168274758-c7505569-c1fc-47bc-bf27-a8000e0d3898.png)

* Weight : 14.2g
* Dimensions : 46 x 53mm
* MCU : 170 MHz 32 bit STM32G4
* Input voltage : 10-44V
* Communication : 5Mbps CAN-FD
* Sensor included : Hall
* [More informations](https://mjbots.com/products/moteus-r4-11)
* Order : [mjbots](https://mjbots.com/products/moteus-r4-11)

## Tinymovr R5
![Screenshot 2022-05-13 at 13-42-11 Tinymovr Motor Controller R5](https://user-images.githubusercontent.com/103576080/168276600-a3aacbd0-bd04-4c18-b52e-07ab5077683a.png)

* Weight : 10g
* Dimensions : 36 x 40mm
* MCU : 50MHz 32-bit ARM Cortex M4F
* Input voltage : 12-38V
* Communication : CAN(1Mbps)/UART/SPI 
* Sensor included : Hall
* Open Source Firmware
* [More informations](https://tinymovr.com/products/tinymovr-r5)
* Order : [Tinymovr](https://tinymovr.com/products/tinymovr-r5)
