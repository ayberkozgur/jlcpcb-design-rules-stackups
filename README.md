jlcpcb-design-rules-stackups
============================

JLCPCB design rules and stackups for Altium Designer.

Design rules include:

  - 2 layer
    - 1 oz copper: 5mil trace & clearance, 0.3mm hole, 0.6mm via diameter
    - 2 oz copper: 8mil trace & clearance, 0.3mm hole, 0.6mm via diameter
  - 4 layer
    - 1 oz copper on top & bottom layers: 3.5mil trace & clearance on all layers, 5mil via clearance, 0.2mm hole, 0.45mm via diameter
    - 2 oz copper on top & bottom layers: 3.5mil trace & clearance on mid layers, 5mil via clearance, 8mil trace & clearance on top & bottom layers, 0.2mm hole, 0.45mm via diameter
  - 6 layer
    - 1 oz copper on top & bottom layers: 3.5mil trace & clearance on all layers, 5mil via clearance, 0.2mm hole, 0.45mm via diameter
    - 2 oz copper on top & bottom layers: 3.5mil trace & clearance on mid layers, 5mil via clearance, 8mil trace & clearance on top & bottom layers, 0.2mm hole, 0.45mm via diameter

Layer stackups include:

  - 2 layer
    - 1 oz copper
      - 0.4mm, 0.6mm, 0.8mm, 1.0mm, 1.2mm, 1.6mm, 2.0mm
    - 2 oz copper
      - 1.6mm, 2.0mm
  - 4 layer
      - JLC7628
        - 1 oz copper on top & bottom layers
          - 0.8mm, 1.0mm, 1.2mm, 1.6mm, 2.0mm
        - 2 oz copper on top & bottom layers
          - 1.6mm, 2.0mm
      - JLC2313
        - 1 oz copper on top & bottom layers
          - 0.8mm, 1.0mm, 1.2mm, 1.6mm
        - 2 oz copper on top & bottom layers
          - 1.6mm
  - 6 layer
    - JLC2313
      - 1 oz copper on top & bottom layers
        - 1.2mm, 1.6mm, 2.0mm
      - 2 oz copper on top & bottom layers
        - 1.6mm, 2.0mm

Information compiled from:

  - https://jlcpcb.com/capabilities/Capabilities
  - https://jlcpcb.com/client/index.html#/impedance
  - https://jlcpcb.com/quote/pcbOrderFaq/Copper%20Weight
  - https://jlcpcb.com/quote
  - https://support.jlcpcb.com/article/42-how-to-export-altium-pcb-to-gerber-files
