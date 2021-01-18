[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Real-Time Counter (RTC) Examples (Microchip Studio)

  This repository contains examples of bare metal source code for the Real-Time Counter (RTC), as described in [TB3213 - Getting Started with Real-Time Counter (RTC)](http://ww1.microchip.com/downloads/en/AppNotes/TB3213-Getting-Started-with-RTC-90003213A.pdf) document from Microchip. The repository contains a Microchip Studio solution with multiple projects inside:

  * [<strong>Overflow Interrupt:</strong>](Overflow_Interrupt) This use case demonstrates how to use the RTC Overflow Interrupt to toggle an LED each time the interrupt occurs (for more details, see [<strong>Overflow_Interrupt</strong>](Overflow_Interrupt)).
  * [<strong>Periodic Interrupt:</strong>](Periodic_Interrupt) This use case shows how to use the Periodic Interrupt Timer function of the RTC. An LED is toggled each time the Periodic Interrupt occurs (for more details, see [<strong>Periodic_Interrupt</strong>](Periodic_Interrupt)).
  * [<strong>PIT Wake From Sleep:</strong>](PIT_Wake_From_Sleep) This use case demonstrates how to use the PIT function to wake up the CPU from Sleep. When the CPU wakes up, an LED is toggled (for more details, see [<strong>PIT_Wake_From_Sleep</strong>](PIT_Wake_From_Sleep)).

## Related Documentation
More details and code examples on the ATMEGA4809 can be found at the following links:
- [TB3213-Getting Started with Real-Time Counter (RTC)](http://ww1.microchip.com/downloads/en/AppNotes/TB3213-Getting-Started-with-RTC-90003213A.pdf)
- [ATMEGA4809 Product Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)
- [ATMEGA4809 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=atmega4809)
- [ATMEGA4809 Project Examples in START](https://start.atmel.com/#examples/ATMEGA4809XplainedPro)


## Software Used
- Microchip Studio 7.0.2542 or newer [(https://www.microchip.com/mplab/microchip-studio)](https://www.microchip.com/mplab/microchip-studio)
- ATmega_DFP 1.6.364 or newer Device Pack


## Hardware Used
- ATMEGA4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)
