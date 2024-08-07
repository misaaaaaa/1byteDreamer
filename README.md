# 1byteDreamer
Sintetizador controlado por 1byte
## Especificaciones
- Secuenciador de irregular ritmo y frecuencia
- 8 voltajes disponibles según banco de potenciómetros (trims)
- El voltaje del VCO es decidido según el número construido por 3 bits
- Control manual de cada bit por medio de botones
- 2 rangos de frecuencia posibles
- Filtro controlado por potenciómetro o luz
- Control de nivel de salida
- Salida de línea
- Salida de VCO
- Salida de cada oscilador disponible
## Esquemático

[![Esquemático](sch_img.png)](https://github.com/misaaaaaa/1byteDreamer/blob/main/1byteDreamer_sch.pdf)

## Video de referencia (enlace externo)
[![VideoReferencia](video_img.png)](https://youtu.be/sprBOqf9Ims)
## Imágenes PCB
![FrentePCB](1byteDreamer_front.png)
![TraseraPCB](1byteDreamer_back.png)

## Lista de materiales

|Item|Qty|Referencia                                                                  |Valor             |Tipo de ítem               |Huella                             |
|----|---|----------------------------------------------------------------------------|------------------|---------------------------|-----------------------------------|
|1   |17 |R1, R2, R3, R4, R5, R7, R8, R12, R13, R14, R15, R16, R17, R18, R19, R20, R21|1k                |Resistencia SMD            |SMD 0805                           |
|28  |1  |U5                                                                          |L7805             |Regulator_Linear:L7805     |TO-252                             |
|2   |2  |U1, U3                                                                      |Base 14p          |Socket DIP                 |DIP-14                             |
|3   |2  |U2, U4                                                                      |Base 16p          |Socket DIP                 |DIP-16                             |
|4   |4  |R6, R9, R10, R11                                                            |100k              |Resistencia                |6.3mm                              |
|5   |1  |C11                                                                         |100n              |Condensador                |7x2.5mm P=5mm                      |
|6   |2  |C4, C6                                                                      |10n               |Condensador                |7x2.5mm P=5mm                      |
|7   |1  |C5                                                                          |47n               |Condensador                |7x2.5mm P=5mm                      |
|8   |1  |C7                                                                          |22n               |Condensador                |7x2.5mm P=5mm                      |
|9   |3  |D4, D5, D6                                                                  |1n4148            |Diodo                      |DO-35                              |
|10  |1  |D8                                                                          |1n4007            |Diodo                      |DO-41                              |
|11  |5  |D1, D2, D3, D7, D9                                                          |Led               |LED                        |Led 3mm                            |
|12  |8  |TRIM1, TRIM2, TRIM3, TRIM4, TRIM5, TRIM6, TRIM7, TRIM8                      |100k              |Trim pot                   |Piher_PT-6-V_Vertical              |
|13  |1  |R22                                                                         |LDR               |LDR                        |LDR_5.1x4.3mm_P3.4mm_Vertical      |
|14  |3  |RV1, RV2, RV3                                                               |500k              |Potenciómetro              |Bourns_PTV09A-1_Single_Vertical    |
|15  |2  |RV4, RV5                                                                    |100k              |Potenciómetro              |Bourns_PTV09A-1_Single_Vertical    |
|16  |9  |C1, C2, C3, C8, C10, C12, C13, C14, C15                                     |10u               |Condensador Electrolítico  |CP_Radial_D5.0mm_P2.50mm           |
|17  |1  |C9                                                                          |100u              |Condensador Electrolítico  |CP_Radial_D5.0mm_P2.50mm           |
|18  |3  |Q1, Q2, Q3                                                                  |PN2222A           |Transistor                 |TO-92                              |
|19  |1  |J5                                                                          |01x06conn         |Pin Header                 |F 2.54mm                           |
|20  |2  |J1, J2                                                                      |AudioJack         |Jack Audio                 |Jack_3.5mm_CUI_SJ1-3525N_Horizontal|
|21  |1  |J3                                                                          |Barrel_Jack_Switch|Jack DC                    |BarrelJack_Horizontal 2.1mmC       |
|22  |6  |SW1, SW3, SW5, SW7, SW8, SW9                                                |SW_SPDT           |Switch                     |SS12D00                            |
|23  |3  |SW2, SW4, SW10                                                              |SW_Push           |Botón                      |SW_PUSH_6mm  PTS645 Straight       |
|24  |1  |U1                                                                          |HEF4093B          |4xxx:HEF4093B              |DIP-14                             |
|25  |1  |U3                                                                          |LM324             |Amplifier_Operational:LM324|DIP-14                             |
|26  |1  |U2                                                                          |4051              |4xxx:4051                  |DIP-16                             |
|27  |1  |U4                                                                          |4046              |4xxx:4046                  |DIP-16                             |
|29  |4  |H1, H2, H3, H4                                                              |M3                |Perno                      |M3                                 |
|30  |4  |H1, H2, H3, H4                                                              |M3                |Tuerca                     |M3                                 |
|31  |4  |H1, H2, H3, H4                                                              |M3                |Golilla                    |M3                                 |
