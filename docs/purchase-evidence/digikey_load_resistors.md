# Digi-Key Load Resistor Evidence

The local Digi-Key shopping-cart records identify the purchased load options used during SMPS testing.

| Value | Manufacturer part | Digi-Key part | Rating | Use in this repository |
|---:|---|---|---|---|
| 47 ohm | TE Connectivity ROX5SSJ47R | A142768CT-ND | 5 W | First load step; also used in clamp |
| 10 ohm | Yageo SQP500JB-10R | 10W-5-ND | 5 W | Intermediate load step |
| 5.6 ohm | Yageo SQP500JB-5R | 5.6W-5-ND | 5 W | Final output-load capture |
| 16.2 ohm | KOA Speer MF1/4DCT52R16R2F | 2019-MF1/4DCT52R16R2FCT-ND | 0.25 W | Purchased resistor candidate |

The stepped sequence was 47 ohm -> 10 ohm -> 5.6 ohm. At the measured 4.94 V scope result, the calculated currents were approximately 105 mA, 494 mA, and 882 mA respectively. The final documented capture therefore uses the 5.6 ohm, 5 W resistor and represents approximately 0.882 A calculated load current and 4.36 W calculated load power. It does not claim certified or sustained 1 A operation.

The 47 ohm TE Connectivity ROX5SSJ47R (A142768CT-ND) is documented separately as the drain-clamp series resistor, not as the final output load.

