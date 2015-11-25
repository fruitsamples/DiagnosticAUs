### DiagnosticAUs ###

===========================================================================
DESCRIPTION:

The DiagnosticAUs project contains targets for twhree diagnostic audio units: AUValidSamples, AUPulseDetector, and DebugDispatcher. The DebugDispatcher unit just passes audio through, the AUPulseDetectorr is also a pass through unit but uses a pulse output to detect latency, and the AUValidSamples unit is a pass through that validates the incoming samples as the arrive.

===========================================================================
BUILD REQUIREMENTS:

Mac OS X v10.6 or later

===========================================================================
RUNTIME REQUIREMENTS:

Mac OS X v10.6 or later

===========================================================================
PACKAGING LIST:

AUPulseDetector.cpp
- Implemention for the AUPulseDetector unit

AUPulseDetectorView.cpp
- Cocoa view for the AUPulseDetector unit

AUValidSamples.cpp
- Implemention for the DebugDispath unit

AUValidSamplesView.cpp
- Cocoa view for the AUValidSamples unit

DebugAU.cpp
- Implemention for the DebugDispath unit

===========================================================================
CHANGES FROM PREVIOUS VERSIONS:

Version 1.0
- First version.

===========================================================================
Copyright (C) 2009 Apple Inc. All rights reserved.
