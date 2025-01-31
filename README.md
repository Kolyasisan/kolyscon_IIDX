# kolyscon_IIDX
FreeCAD files for kolyscon_IIDX - a Double Player IIDX controller with AC-size turntables.

# General Info
This project was designed to be printable with medium-sized printers of 220x220 XY build volumes. Some parts are split and are modular, with fixation done via bolting and/or dovetail joints. Most of the controller properties are stored in a shared Properties file. Uses Omron's E6B2 series of optical encoders for the turntable.

# Warning
* Do note that this is very much a WIP and a hacky personal project. Expect some degree of questionable choices and some boilerplate work needed for exports from FreeCAD. Not quite a kung-fu master of optimal FreeCAD project organization.
* The project has been designed with a certain set of build items (like mount holes fo specific type-c extenders, PCB mounts of my own PCB, etc.). It's recommended for you to tweak the project to suit your own materials.
* The properties file has been introduced mid-way, so some files still use local property spreadsheets, but getting rid of them is in the works.
* 1P and 2P buttons are not as long as on AC, I shrunk them down because it wouldn't fit on my desk otherwise. AC accurate distances can be restored by weaking a couple parameters though. P.S., beware of printing tolerances as well.
* This conntroller was designed with my own needs in mind. For example, it features translucent lightmeshes for lighting strips, which you may not need.
* If you ever decide to print it, with or without modifications, please assemble your exported models first to verify correctness of all parts.
* This project initially became as a personal attempt of fixing some of the parts on my Phoenixwan controller. As a result, a couple of parts are replicas of PW's design, specifically the 2 bottom turntable parts. A simpler version of the turntable assembly is coming soon.
* Because of all of this, for all intents and purposes, consider this as a reference project. This is NOT production ready, you won't be able to print it out of the box directly!! At least for now.

# Attribution
This project was built from the ground up with the help of some references from the excellent GJ-Tho-Modular-V2 project (https://github.com/thomasstar/GJ-Tho-Modular-V2) and some help from the Cons&Stuff community. Y'all GREAT!!
