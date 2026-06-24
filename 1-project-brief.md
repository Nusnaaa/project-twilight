# Drone Project Brief — Early Concept

This project is focused on designing and developing a small unmanned aircraft/drone intended primarily for operation in Ghanaian conditions. The aim is to create a practical, low-altitude aircraft that can carry a small removable sensor or camera payload for basic survey, monitoring, mapping, or data-gathering missions.

The drone is still at an early concept stage, so the requirements below are not final. They are starting targets to guide the first round of design, sizing, research and component selection.

## Intended operating context

The drone is being designed with Ghanaian operation in mind. This matters because the aircraft may need to operate in hotter weather, dustier environments, more humid conditions, and from less prepared launch and recovery areas than a typical hobby drone flown from a smooth field or runway.

The aircraft is expected to operate at low altitude, with an initial target operating altitude of around **100 m** and a maximum altitude of around **120 m** in line with UK CAA regulations.

## Initial performance targets

The first version of the drone is being designed around the following rough targets:

| Area               |                                                                     Target |
| ------------------ | -------------------------------------------------------------------------: |
| Payload            |                           Around **500 g** removable camera/sensor payload |
| Endurance          |                                                      Minimum of **1 hour** |
| Range              |                               Around **10 km** if flown in a straight line |
| Cruise speed       |                                                          Around **10 m/s** |
| Maximum speed      |                                                          Around **22 m/s** |
| Operating altitude |                                                           Around **100 m** |
| Maximum altitude   |                                                           Around **120 m** |
| Launch method      |                    From an unpaved or poorly paved road/runway if possible |
| Recovery method    | Similar rough-surface recovery, or another practical field recovery method |

The 500 g payload target is meant to represent a small removable module, such as a camera, basic mapping sensor, environmental sensor, or test mass. It is not yet tied to one specific sensor package.

## Design approach

The first version of the drone will prioritise practicality over originality. The aim is to get a working aircraft designed, built, tested and improved, rather than trying to design every subsystem from scratch immediately.

Version 1 will therefore use mostly **off-the-shelf components**, especially for flight-critical systems such as:

| System             | Version 1 approach                               |
| ------------------ | ------------------------------------------------ |
| Flight controller  | Off-the-shelf/open-source-compatible controller  |
| Motors and ESCs    | Off-the-shelf                                    |
| Servos/actuators   | Off-the-shelf                                    |
| Battery system     | Off-the-shelf                                    |
| Radio/control link | Off-the-shelf                                    |
| Autopilot/software | Open-source and existing tools where appropriate |

For software and embedded systems, Version 1 will use a mixture of:

1. **open-source software**, especially where it improves safety, reliability or development speed;
2. **my own code**, mainly for non-critical systems, testing, data logging, analysis, payload support, or experimental features.

Later versions of the project will gradually reduce reliance on systems I have not personally designed or modified. The long-term aim is to move towards a deeper understanding and greater ownership of the aircraft’s software, embedded systems, electronics and design tools.

## Future Development

The first version is not intended to be a fully custom, production-ready drone. It is also not intended to use fully custom electronics, fully custom flight software, or highly optimised aerospace manufacturing methods from the beginning.

Instead, the project will develop in stages:

| Version | Main goal                                                                               |
| ------- | --------------------------------------------------------------------------------------- |
| V1      | Build a safe, working drone using mostly off-the-shelf parts and open-source tools      |
| V2      | Improve performance, payload integration, reliability and maintainability               |
| V3+     | Gradually introduce more custom software, electronics, manufacturing and design control |


