# Autonomous Vehicle: Gantt Chart

This project houses the gantt chart for MWHS Autonomous Vehicle team.

## Contributing
The gantt chart is generated through [GanttProject]. **DO NOT** edit the chart
by hand. Such task would be counterproductive *and* destructive to the structure
of this repository.

### Installing Java Virtual Machine
GanttProject is built on Java.

#### Windows and macOS
Download the Java SE 8 JRE installer from this [page][java-d]. At the time of
writing, the latest version of Java SE is Java SE 8u191. Follow the installer
prompt to install Java.

### Installing GanttProject
GanttProject has cross-platform support. Follow one of the guides bellow to get
started.

#### Windows
Download the latest GanttProject distribution for Windows from this
[page][gp-d]. At the time of writing, the latest stable version of GanttProject
is v2.8.9. The latest distribution file for Windows is
`ganttproject-2.8.9-r2335.exe`. Download and run the installation file.

#### macOS
Download the latest GanttProject ZIP distribution from this [page][gp-d]. At the
time of writing, the latest stable version of GanttProject is v2.8.9. The latest
zip distribution file is `ganttproject-2.8.9-r2335.zip`.

Extract the contents of the zip archive to your home directory (tip: open finder
and press <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>H</kbd> to locate your home
directory).

Open terminal (tip: press <kbd>⌘</kbd> + <kbd>␣</kbd> to open spotlight search,
then type "Terminal" and press <kbd>↩</kbd>). Enter the command
`nano ~/.bash_profile`. Append the following into the file.
``` bash_profile
alias ganttproject=~/<enter GanttProject folder name here>/ganttproject
```
Press <kbd>⌃</kbd> + <kbd>X</kbd> followed by <kbd>Y</kbd> to save and
<kbd>↩</kbd> to save into the original file.

Exit the terminal and reopen it. Launch GanttProject by using the following
command `ganttproject`.

### Exporting the gantt chart
Follow the following steps in order to produce the proper chart.

1. Export the chart as HTML report. Set the theme as `Samara`. Set the file name
and the path to `docs/index.html`.
2. Export the chart as a raster image file. Set the file format to `PNG`. Set
the file name and the path to `docs/index.png`. Set the start date to the
beginning of the working week of the actual start date and the end date as the
end of the working week for the actual end date of the project.
3. Commit and push.

[GanttProject]: https://github.com/bardsoftware/ganttproject
[java-d]: https://www.oracle.com/technetwork/java/javase/downloads/index.html
[gp-d]: https://github.com/bardsoftware/ganttproject/releases
