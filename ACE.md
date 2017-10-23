# Configuration
## TR_ClockParser plugin - v1.2 - by Toby R <img src='c2addon\files\TR_ClockParser\PluginIcon.ico' alt='Icon'>
Property | Value
:---: | ---
Description | Plugin that parses seconds to clock string.
Category | Time
Cordova | No
Flags | No
Help | http://www.neexeen.com/
Id | TR_ClockParser
Rotatable | No
Type | object

# Actions
#### There is 0 actions available
# Conditions
#### There is 0 conditions available
# Expressions
#### There are 4 expressions available
**Time::Minimal** : Return the smallest possible clock string. e.g.: Minimal(30) -> "30", Minimal(90) -> "01:30", Minimal(4830) -> "01:20:30"

* **0** : Number of seconds to parse.

---

**Time::MMSS** : Return the "MM:SS" clock string. e.g.: MMSS(30) -> "00:30", MMSS(90) -> "01:30", MMSS(4830) -> "80:30"

* **0** : Number of seconds to parse.

---

**Time::HHMMSS** : Return the "HH:MM:SS" clock string. e.g.: HHMMSS(30) -> "00:00:30", HHMMSS(90) -> "00:01:30", HHMMSS(4830) -> "01:20:30"

* **0** : Number of seconds to parse.

---

**Time::ToSeconds** : Converts the specified clock string to seconds e.g.: "01:03:30" -> 3810, "15:30" -> 930, "30" -> 30

* **** : String representation of time in one of the following formats: "HH:MM:SS", "MM:SS", "SS".

---


