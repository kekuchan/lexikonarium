# Overview

Lexikonarium is about creating dictionaries 
for self learning purposes. Learnt expressions 
with informations can be added, and quickly 
looked upon them, if found in some given text.

The name Lexikonarium is from the Greek lexiko,
and the Latin dictionarium, both meaning dictionary.

# Technical details 

Lexikonarium was designed to load a file, 
containing the dictionaries into the memory,
and using it directly for fast lookups. When 
only one dictionary is contained, it saves 
space by not having to keep referencing it. 
For editing however it has to be converted 
to an editable format. Thus it was designed 
for smaller dictionaries, otherwise a different 
architecture would be needed to read and write 
to them in smaller parts.

# Tutorial

To access the menu, tap or click the top "Menu" 
bar. Choose "Add/Find", and type "Greek" for the 
dictionary, "lexiko" for the expression and 
"dictionary" for the meaning, and choose "Add".
Add another by typing "Latin" for the dictionary,
"dictionarium" for the expression and "dictionary" 
for the meaning, and again choose "Add". Now we 
have two dictionaries ("Greek" and "Latin"), two 
expressions ("lexiko" and "dictionarium") and a
meaning ("dictionary"). To exit the menu, tap or 
click "Cancel", then "Cancel" again. Now by typing 
in the empty area right above the "Menu" button,
some text containing the words "lexiko" or 
"dictionarium", and then putting the cursor before 
the first letter of these words, their meaning is 
looked up and displayed above.

Save the dictionaries in the menu with "Save", "/",
"/" (or choose another path), "New file", type in
some name ending with ".laf" (Lexikonarium archive 
file), choose "Create", tap or click on the created 
".laf" file, and choose "Select". Optionally type in
some comment, and choose "Save". Creating a backup 
as a safety measure is done with choosing the saved 
path, then the ".laf" file, and "Download". To exit 
the menu, tap or click "Cancel".

To load a saved ".laf" file, choose in the menu 
"Load", "/", tap or click on the ".laf" file (or 
upload a backup file before that by choosing the 
folder path and "Upload file"), then "Select" and 
"Load". This overwrites any of the currently used 
dictionaries, expressions and meanings with those 
in the ".laf" file. To exit the menu, tap or click 
"Cancel". If editing is needed, then the loaded 
".laf" file has to be converted in the menu with 
"Edit" and "Convert". To exit the menu, tap or click 
"Cancel".

# Change logs 

[/docs/log/2023.md](2023).

# Contribute

Read [/docs/CONTRIBUTE.md](CONTRIBUTE.md).

# Software license

Copyright (c) 2022-2023 Lexikonarium contributors

Redistribution and use in source and binary forms,
with or without modification, are permitted
provided that the following conditions are met:

1. Redistributions of source code must
retain the above copyright notice, this list
of conditions and the following disclaimer.

2. Redistributions in binary form must
reproduce the above copyright notice,
this list of conditions and the following 
disclaimer in the documentation and/or other 
materials provided with the distribution.

Subject to the terms and conditions of this
license, each copyright holder and contributor
hereby grants to those receiving rights under this
license a perpetual, worldwide, non-exclusive,
no-charge, royalty-free, irrevocable (except for
failure to satisfy the conditions of this license)
patent license to make, have made, use, offer to
sell, sell, import, and otherwise transfer this
software, where such license applies only to
those patent claims, already acquired or hereafter
acquired, licensable by such copyright holder or
contributor that are necessarily infringed by:

(a) their Contribution(s) (the licensed
copyrights of copyright holders and
non-copyrightable additions of contributors,
in source or binary form) alone; or

(b) combination of their Contribution(s)
with the work of authorship to which such
Contribution(s) was added by such copyright
holder or contributor, if, at the time the
Contribution is added, such addition causes
such combination to be necessarily infringed.
The patent license shall not apply to any other
combinations which include the Contribution.

Except as expressly stated above, no rights or
licenses from any copyright holder or contributor
is granted under this license, whether expressly,
by implication, estoppel or otherwise.

DISCLAIMER

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS
AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
SUCH DAMAGE.

# Documentation license

Copyright (c) 2022-2023 Lexikonarium contributors

Redistribution and use in source and binary forms,
with or without modification, are permitted
provided that the following conditions are met:

1. Redistributions in source form must
retain the above copyright notice, this list
of conditions and the following disclaimer.

2. Redistributions in binary form must
reproduce the above copyright notice,
this list of conditions and the following 
disclaimer in the documentation and/or other 
materials provided with the distribution.

Subject to the terms and conditions of this
license, each copyright holder and contributor
hereby grants to those receiving rights under this
license a perpetual, worldwide, non-exclusive,
no-charge, royalty-free, irrevocable (except for
failure to satisfy the conditions of this license)
patent license to make, have made, use, offer to
sell, sell, import, and otherwise transfer this
documentation, where such license applies only to
those patent claims, already acquired or hereafter
acquired, licensable by such copyright holder or
contributor that are necessarily infringed by:

(a) their Contribution(s) (the licensed
copyrights of copyright holders and
non-copyrightable additions of contributors,
in source or binary form) alone; or

(b) combination of their Contribution(s)
with the work of authorship to which such
Contribution(s) was added by such copyright
holder or contributor, if, at the time the
Contribution is added, such addition causes
such combination to be necessarily infringed.
The patent license shall not apply to any other
combinations which include the Contribution.

Except as expressly stated above, no rights or
licenses from any copyright holder or contributor
is granted under this license, whether expressly,
by implication, estoppel or otherwise.

DISCLAIMER

THIS DOCUMENTATION IS PROVIDED BY THE COPYRIGHT HOLDERS
AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS
DOCUMENTATION, EVEN IF ADVISED OF THE POSSIBILITY OF
SUCH DAMAGE.

Includes text using the same license,
from the SWARMBJECT development environment:
Copyright (c) 2021-2023 SWARMBJECT contributors