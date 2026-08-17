Baseline example for power production

**Key parameters:**
-  wind speed at 6 m height: 6 m/s
-  vertical wind profile: explog
- alpha: 0.08163 # exponent of the wind profile law
- z0: 0.0002 # surface roughness [m]
-  initial tether length: 150 m
-  final tether length: 350 m
- kv: 0.0408 # v_set = kv * sqrt(force)

**Figure eight parameters:**
-  width: 20 °
-  height: 11 °
-  center elevation: 26°
-  minimal elevation: 10 ° (boundary condition, this correspondents to approx 18° minimal center elevation)
-  depower_setpoint: 0.27 
-  max_steering: 0.32 # command limit
I found out that center elevation = 18° gives much more power for the given wind profile. Is 10° minimum at 150 m tether good? Or shall we use a minimal height instead?

### Flight path

<figure style="text-align: center;">
<img src="Pasted%20image%2020260816220753.png" style="width: 70%;">
</figure>

### Time series

![[Pasted image 20260816232338.png]]
### Aerodynamics

![[Pasted image 20260816224821.png]]
### Power

![[Pasted image 20260816233111.png]]