# Override default parameters with:
## Connections to include:
- AVA.-AVB.+
- AVB.-AVA.+
- AS\d+-DA.+
- DA\d+-DB.+
- DB\d+-AS.+
- AVA.-DA.+
- AVB.-DB.+
- DA\d+-M(D|V)(L|R).+
- DB\d+-M(D|V)(L|R).+
- M(D|V)(L|R)\d+-M(D|V)(L|R).+

## Change polarity of connections:
- DB7-AS10: inh
- DB4-AS6: inh
- DB5-AS7: inh
- DB1-AS2: inh
- DB1-AS1: inh
- DB1-AS4: inh
- DB5-AS8: inh
- DB7-AS11: inh
- DB3-AS5: inh
- DB3-AS4: inh
- DB6-AS8: inh
- DB6-AS9: inh
- DB2-AS3: inh

## Inject current:
- Cell: AVBL
    - delay: 50ms
    - end: 1900ms
    - amplitude: 15pA
- Cell: AVBR
    - delay: 50ms
    - end: 1900ms
    - amplitude: 15pA

## Other parameters:
- neuron_to_neuron_exc_syn_conductance: 1.2 nS

