# MSOE-Coding-Standard
The [MSOE EECS Department Java Coding Standards](https://csse.msoe.us/cs1021/codingstandard/), now in native IntelliJ IDEA formats! A few bits from the Google standards that were left out from the MSOE version, as well as some things that are not explicitly stated in the rules but will still lose you points or cause problems are also included.

If you are not using IDEA, you can alternatively use [CheckStyle](https://faculty-web.msoe.edu/jones/MSOE_checkStyle.xml).

## IDE Setup
These are the general steps for setting up an IDE from scratch. If you have already setup IntelliJ IDEA before, you only need steps 3-7.
1. Sign up for the [Github Student Developer Pack](https://education.github.com/pack/).
2. [Activate a free JetBrains educational subscription](https://www.jetbrains.com/student/?authMethod=github) & install IntelliJ IDEA Ultimate using the [Toolbox App](https://www.jetbrains.com/toolbox-app/).
3. Download the [Code Style](https://raw.githubusercontent.com/xDazld/MSOE-Coding-Standard/main/MSOE_Code_Style.xml) & [Inspections](https://raw.githubusercontent.com/xDazld/MSOE-Coding-Standard/main/MSOE_Inspections.xml) XML files.
4. In IntelliJ IDEA, go to: Settings for New Projects. (Each project has its own settings, this changes your default settings when you make a new project).
5. Navigate to: Editor → Code Style → ⚙️ → Import Scheme → IntelliJ IDEA Code Style XML; then find and select the Code Style file you downloaded, and click both OKs. Make sure "MSOE Code Style" is now selected as your scheme. (This controls how your file is formatted).
6. Navigate to: Editor → Inspections → ⚙️ → Import Profile; then find and select the Inspections file you downloaded, and click OK. Make sure "MSOE Inspections" is now set as your profile. (Inspections are the hints the IDE gives you to fix problems).
7. Navigate to: Editor → File and Code Templates → Includes → File Header; then paste the [MSOE Header](https://github.com/xDazld/MSOE-Coding-Standard/blob/main/File%20Header.java.txt) into the text box.
8. Navigate to: Version Control → GitHub → ➕ → Log In via GitHub; then follow instructions to allow IntelliJ IDEA access. (This allows you to work with lab files).
9. Navigate to: Tools → Shared Indexes; then set JDKs and Maven Libraries to "Download automatically". (This makes the IDE load much faster).
10. Save your new settings.
11. Go to: New Projects Setup → Structure.
12. Set the JDK option to the newest version of Liberica. (This enables JavaFX, its source code, and its documentation).
13. Save the settings.

You should now be setup for coding in Java and JavaFX at MSOE.

You may also optionally want to setup Google's [Error Prone](https://errorprone.info/docs/installation#:\~:text=IntelliJ%20IDEA,is%20NOT%20selected.).

If writing code in Word or PowerPoint, you might want to have [JetBrains Mono](https://www.jetbrains.com/lp/mono/#how-to-install) available.
