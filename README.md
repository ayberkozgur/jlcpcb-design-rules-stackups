jlcpcb-design-rules-stackups
============================

JLCPCB design rules and stackups for Altium Designer.

Design rules
------------

  - 2 layer
    - 1 oz copper
      - 5mil trace with & clearance
      - 0.3mm min. hole diameter
      - 0.6mm min. via diameter
      - 0.25mm hole clearance
    - 2 oz copper
      - 8mil trace width & clearance
      - 0.3mm min. hole diameter
      - 0.6mm min. via diameter
      - 0.25mm hole clearance
  - 4 layer
    - 1 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 4mil trace width & clearance on all layers
      - 0.2mm min. hole diameter
      - 0.45mm min. via diameter
      - 5mil via clearance
      - 0.25mm hole clearance
    - 2 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 4mil trace width & clearance on mid layers
      - 8mil trace width & clearance on top & bottom layers
      - 0.2mm min. hole diameter
      - 0.45mm min. via diameter
      - 5mil via clearance
      - 0.25mm hole clearance
  - 6 layer
    - 1 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on all layers
      - 0.2mm min. hole diameter
      - 0.45mm min. via diameter
      - 5mil via clearance
      - 0.25mm hole clearance
    - 2 oz copper on top & bottom layers, 0.5 oz copper on mid layers
      - 3.5mil trace width & clearance on mid layers
      - 8mil trace width & clearance on top & bottom layers
      - 0.2mm min. hole diameter
      - 0.45mm min. via diameter
      - 5mil via clearance
      - 0.25mm hole clearance

All design rules include a `PowerPads` pad class for easy direct polygon pour connection.

Layer stackups
--------------

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

References
----------

  - https://jlcpcb.com/capabilities/Capabilities
  - https://jlcpcb.com/client/index.html#/impedance
  - https://jlcpcb.com/quote/pcbOrderFaq/Copper%20Weight
  - https://jlcpcb.com/quote
  - https://support.jlcpcb.com/article/42-how-to-export-altium-pcb-to-gerber-files
  - https://embdev.net/topic/478351
