# GL-MT300N-V2 (Mango)

The best selling mini router.

MT300N-V2 is an upgraded version of MT300N. The differences include:

* RAM is doubled to 128MB 
* WiFi performance is improved using MTK proprietary driver. This driver doesn't support monitoring mode. But it support layer 2 bridging for all kinds of AP, which is not the case of opensource drivers.
* Opensource Wi-Fi drivers also work but it has some bugs and cause kernel panic. This problem was never solved by the community.  
* No PoE options.

##  Hardware Specification

|                         Model | GL-MT300N-V2                                              |
| ----------------------------: | :-------------------------------------------------------- |
|                           CPU | MTK 7628NN 580MHz                                         |
|                        Memory | DDRII 128MB                                               |
|                       Storage | 16MB NOR Flash                                            |
|                    Interfaces | 1 WAN<br>1LAN 1 USB2.0<br>1 Micro USB (power)<br>1 Reset Button |
|                     Frequency | 2.4GHz                                                    |
|             Transmission Rate | 300Mbps                                                   |
|                 Max. Tx Power | 20dBm                                                     |
|                      Protocol | IEEE 802.11b/g/n                                          |
| External Drive Format Support | FAT32/NTFS/EXT4/EXT3/EXT2                                 |
|                Webcam Support | MJPEG, YUV (not supported from firmware v2.27)            |
|                  DIY Features | UART, 4GPIOs, 3.3V & 5V power port                        |
|      External Antenna Support | No                                                        |
|            PoE Module Support | No                                                        |
|                   Power Input | 5V/2A                                                     |
|             Power Consumption | <2.75W                                                    |
|             Dimension, Weight | 58mmX58mmX25mm, 39g                                       |

## PCB Pinout

The pins on the left side can be actually used for Ethernet port or EMMC. They cannot be used as GPIO.

<div class="gl-lightbox" itemscope itemtype="http://schema.org/ImageGallery">
  <figure itemprop="associatedMedia" itemscope itemtype="http://schema.org/ImageObject">
    <a href="https://static.gl-inet.com/docs/en/2.x/hardware/mt300n-v2/src/GL-MT300N-V2_PINOUT-1.jpg" itemprop="contentUrl" data-size="2339x1654">
      <img src="https://static.gl-inet.com/docs/en/2.x/hardware/mt300n-v2/src/GL-MT300N-V2_PINOUT-1.jpg" itemprop="thumbnail" alt="gl-mt300n-v2 pcb pinout" loading="lazy" />
    </a>
  </figure>
</div>
