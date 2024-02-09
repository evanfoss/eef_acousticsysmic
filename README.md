# EPL Acoustic System Microphone

Much like the Acoustic System Cable it might seem silly to make a whole project on github about putting a connector on a microphone. The thing is we optomized the process for this and we have different microphones so there are different variations of this project. The current version and the one we are first documenting here publicly is uses a Knowles FG microphone. Later we will include information on the EK series but this is not currently a priority as the microphones we used there are no longer manufactured.

This is my fork of the original project here: https://github.com/EPL-Engineering/epl_acousticsysmic

Preassembly Process
===================================

We advise buying the tubing early and unwinding it. The tubing adopts a curl from being on coiled up that is an issue. To properly fit the inside of the acoustic system the tubing needs to not have the memory of this bend in it. To help remove this further we have designed a fixture which keeps the completed microphone assembly straight during the curing process. So please stop here, buy the tubing, make this fixture, and lay the tubing out. Obviously you should not leave anything to rest on top of the tubing as this will also distort it.

Assembly Process
===================================

1. Cut the tubing to length.
2. Insert the tubing into the fixture.
3. Feed the cable for the microphone most of the way through the tubing leaving about 2 inches behind the microphone exposed.
4. Cut the heatshrink off the circumfrence of the microphone but not the cable. (this is not for the faint of heart)
5. Apply RTV to the 1/5" of microphone cable behind the microphone.
6. Pull the microphone back into the tubing until the front of the microphone is flat to the front of the tubing.
7. Wait until the RTV cures while doing steps 8 to .
8. Slide the outer miniDIN5 connector over the unterminated end of the cable with the narrow end facing the circuit board.
9. Strip the unterminated end of the multiconductor cable.
10. Solder the now exposed wires from the cable to the connectors pins. Be careful the connector melts easily.
11. Assemble the connectors internal shielding (the metal inner covers, and the plastic mid one. Do not slide the outer cover on.
12. Plug the connector into the mic. amp. and test that you soldered it correctly.
13. If it works continue to step 14. If it doesn't work disassemble the connector housing and return to step 10. If you already tried this once odds are you broke the microphone at step 4. Get a new microphoen and start over from step 1.
14. Now that you have something that works you can fill the partially assembled connector housing with RTV.
15. Push the outer housing over the inner layers you already assembled.
16. Let the whole thing sit for a day or two to cure and then retest.

Future Work
===================================

We are looking to mold or 3D print the tubing portion of the microphone so that it can fit around the heatshrink the manufacture applied. 

