# Umbra Nera look mechanics

Umbra Nera is a humanoid fashion-doll pet. Her feet, heels, lower torso, four pistols, and long hair mass remain stably registered. The gray-green eyes lead each gaze; eyelids and sharply arched brows reshape subtly, followed by a restrained rigid head/neck turn and a very small upper-torso follow-through. The tall beehive remains vertical and the long hair tail follows the head with slight lag rather than warping. Glasses stay rigidly attached to the face. Hand pistols remain attached and follow the wrists; heel pistols remain locked to the boots. Facial proportions, glasses, beauty mark, and expression must not stretch.

Motion budget: every 22.5-degree step moves pupils, eyelids, head angle, and upper torso by an even small amount. Feet, baseline, body scale, and lower-body anchor do not jump. No whole-sprite rotation or raster warp.

- 000 up: eyes and chin lift; upper eyelids open slightly; more underside of glasses is visible; body remains front-facing.
- 090 screen-right: pupils, nose, chin, and face turn clearly toward the image's right edge; viewer-left cheek becomes more visible, viewer-right cheek is partly occluded; near hand pistol stays attached and becomes slightly more side-on.
- 180 down: eyes and chin lower; upper eyelids descend and glasses tilt only with the rigid head; more forehead/beehive base is visible.
- 270 screen-left: pupils, nose, chin, and face turn clearly toward the image's left edge; viewer-right cheek and beauty mark remain correctly placed and visible when anatomy permits; viewer-left cheek is partly occluded; near pistol follows the wrist.

Diagonals interpolate these four pose families continuously. Hair and ribbons lag slightly but remain attached. No cardinal may read as neutral/front.
