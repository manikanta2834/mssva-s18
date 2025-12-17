# Flag 3 – Runtime Function Resolution Tampering

## Invariant
Runtime function resolution should remain consistent with expected static mappings after program initialization.

## Telemetry
Dynamic symbol resolution and indirect function calls were monitored to detect runtime redirection or tampering.

## Observation
**Observed.**  
Function resolution behavior differed from expected mappings, indicating possible runtime manipulation.

## Security Impact
Tampering with runtime resolution can redirect execution to unintended or malicious code paths, enabling stealthy attacks.

## Limitations
This analysis cannot clearly distinguish between intentional dynamic behavior and malicious manipulation without deeper semantic analysis.
