HexaChord is a java software dedicated to music analysis and composition through generalized Tonnetz representations. Check the [presentation web page](https://louisbigo.com/hexachord).

# Build

The whole project can be built with the software `ant`. Just run the command `ant` from the directory `HexaChord`. It will use the file `build.xml` to compile the whole project.

# Run

Once the project has been built, do the following from the `hexachord` directory:

1. get the path of Java used by your computer by running the command `which java` in a terminal
2. in the file `run_HexaChord.sh` change the expression `/usr/bin/java` by the path you got (if different)
3. give execution rights to the script `run_HexaChord.sh` by running `chmod +x run_HexaChord.sh`
4. run the command `./run_HexaChord.sh`

# Software documentation

See the [presentation page](https://louisbigo.com/hexachord).

# Extensions and improvements
1. Add rotations of the Tonnetz, mirroring, and default industry standard Tonnetz representation. (Currently under development)
2. Add a way to save the Tonnetz as a video.
3. Add multiple Tonnetz layers for Jazz chords.

For more details, see the [documentation](./HexaChord_Extensions.pdf).