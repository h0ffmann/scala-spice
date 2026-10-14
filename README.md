> **archived.** this repository is not maintained: 15 commits, from november 2017 to july 2020. nothing here was built or run again for this notice, so read it as a record and not as a tool.
>
> its own description: "circuit analysis using scala-lang". it is mostly Scala and CSS. it has no licence file, so no licence is given for it.
>
> where the work is now:
>

| what | where |
|---|---|
| the whole story, with every work | [h0ffmann.github.io/h0ffmann](https://h0ffmann.github.io/h0ffmann/), doi [10.5281/zenodo.23352630](https://doi.org/10.5281/zenodo.23352630) |
| the sea, in Scala 3 | [marola.dev](https://marola.dev), doi [10.5281/zenodo.23224155](https://doi.org/10.5281/zenodo.23224155) |
| a wave model on GPUs | [ww3-gpu](https://h0ffmann.github.io/ww3-gpu/), doi [10.5281/zenodo.23221351](https://doi.org/10.5281/zenodo.23221351) |
| a benchmark for forecasts of the brazilian coast | [marola-bench](https://github.com/marola-dev/marola-research/tree/main/marola-bench), doi [10.5281/zenodo.23352633](https://doi.org/10.5281/zenodo.23352633) |
| the tools that build the rest | [picasso](https://github.com/h0ffmann/picasso), doi [10.5281/zenodo.23311208](https://doi.org/10.5281/zenodo.23311208) |
| a book on closed source | [closed source: the god that failed](https://h0ffmann.github.io/closed-source/), doi [10.5281/zenodo.23333656](https://doi.org/10.5281/zenodo.23333656) |

---

# Scala Spice

Circuit Analysis using Scala.

## Setting up jar file

[Solution IntelliJ](https://stackoverflow.com/questions/2025607/how-to-create-a-jar-file-or-export-jar-on-intellij-like-eclipse-java-archive-e)

```
File >> Project Structure >> Artifacts >> Add option
Choose correct MANIFEST.MF path and Main Class

```

Jar file created at: /scala-spice/classes/artifacts/spice_jar/spice.jar

```
java -jar <jar file>
```

## TODO
- Test Windows clear
- .JAR to .EXE convert
- Implement Gauss Jordan elimination
- Improve imports to make .jar smaller