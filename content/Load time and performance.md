All times measured on Desktop PC
## Load times
Tested 13 August 2026

### Without system image

Package load time: 11.8 s
Starting simulation loop: 17.22 s

**Remark:** The second number includes the first one.

### With system image

Package load time: 0.81 s
Starting simulation loop: 6.19 s

## Performance

Executing:
```julia
include("examples/simple_fig8.jl")
```
### Without tubulence
  
Performance: 90.0 s sim in 40.2 s wall = 2.24 x realtime (4.5 ms/step over 9000 steps at dt = 0.0100 s, vsm_interval = 10)
Performance: 150.0 s sim in 66.6 s wall = 2.25 x realtime (4.4 ms/step over 15000 steps at dt = 0.0100 s, vsm_interval = 10)
### With 50% turbulence
Performance: 90.0 s sim in 47.9 s wall = 1.88 x realtime (5.3 ms/step over 9000 steps at dt = 0.0100 s, vsm_interval = 10)
  
 

