# Regenerating FFXI's OSS License File

![image](https://github.com/cmboling/final-fantasy-xvi-fossafied-notice/assets/1427948/09a0d519-52d8-44b8-ab0f-d4decd02c20b)

A project demonstrating the use of [FOSSA](https://fossa.com/) to regenerate [FFXVI's OSS license file](https://www.youtube.com/shorts/upOlWzI2jlQ). This is the side quest we've all been waiting for!

## Prerequisites

 - [ ] Engage in the playing of the FFXVI soundtrack, [at this designated location](https://www.youtube.com/watch?v=58lNeY2Gpqk&list=PLFHRxdgR3MH8JOUcavLuNgfCTzkXCjUQQ&index=3); this repository shall duly furnish it for your enjoyment.
 - [ ] The FOSSA CLI eluded discovery at Charon's Toll; nevertheless, indications suggest its possible presence [here](https://github.com/fossas/fossa-cli). Procure it.
 - [ ] Industrious and zealous Blackthorne is unable to contrive FOSSA API tokens. However, he possesses knowledge that the preeminent FOSSA API token can be forged within the precincts of the FOSSA UI, referencing this [artefact](https://docs.fossa.com/docs/api-reference#push-only-api-token) he happened upon.
 - [ ] Replicate this repository employing Phoenix capabilities.
 
 ## Come To Me, Ifrit!
 
 In unison with your retinue, equip your token and employ the command `fossa analyze` amidst the throes of epic battle. Here's an example output:

 ```
➜  final-fantasy-xvi-fossafied-notice git:(main) ✗ fossa analyze

Scan Summary
------------
fossa-cli version 3.8.6 (revision b2657cb78351 compiled with ghc-9.0)
fossa endpoint server version: 4.14.9

1 projects scanned;  0 skipped,  1 succeeded,  0 failed,  0 analysis warnings

-
* fossa-deps file analysis: succeeded
  ** https://github.com/ben-strasser/fast-cpp-csv-parser (reference)
  ** https://github.com/google/flatbuffers (reference)
  ** https://github.com/harfbuzz/harfbuzz (reference)
  ** https://github.com/microsoft/Directxtex (reference)
  ** https://github.com/khronosgroup/vulkan-headers (reference)
  ** https://github.com/libigl/eigen (reference)

  Some projects may not appear in the summary if they were filtered during discovery.
  You can run `fossa list-targets` to see all discoverable projects.

You can pass `--debug` option to eagerly show all warning and failure messages.
You can also view analysis summary with warning and error messages at: "/private/var/folders/lg/torgalandkupoarefriends/T/fossa-analyze-scan-summary.txt"
------------

Using project name: `https://github.com/cmboling/final-fantasy-xvi-fossafied-notice.git`
Using revision: `ec8500656100b7a9f1680803ebb4f1a90cdcb2a0`
Using branch: `main`
============================================================
```

## Why, the beast has the appetite of a behemouth! 😜

Behold, presented herein is a [public report](https://app.fossa.com/reports/cf26a84d-fd9a-41ed-8f7f-1728a97b92e3), meticulously generated by the auspices of FOSSA. Though not an exact correspondence to FFXVI's license file, it does unveil certain among the discovered licenses associated with these software packages, and beyond. By way of example, within the license file of FFXVI, the obligations to the `HarfBuzz` package stipulate, "For parts of HarfBuzz that are licensed under different licenses see individual filenames COPYING in subdirectories where applicable." Both the FOSSA user interface and the aforestated report reveal such intricacies; typically overseen by Open Source Program Offices (OSPOs), legal practitioners of Open Source Software (OSS), or external counsel, this data is commonly processed to gain further clarity regarding the usage of the software packages. In its entirety, FOSSA adeptly discerned the licenses applicable to each software package, subsequently presenting them within a commendatory dossier. These two forms of reports offer an array of resemblances and disparities. Please feel unreservedly welcome to inaugurate a GitHub Issue to foster supplementary discourse upon this matter.

## My wounds, Torgal!

- Ensure that the analysis is conducted at the foundation of this repository.
- Verify that your API token has been established.
- Should you encounter persistent difficulties, do not hesitate to consult the Founder!


### References
- [README Image](https://finishing-touch.tumblr.com/post/716624527409496064/all-aboard-the-ffxvi-hype-train)
- [FOSSA documentation](https://docs.fossa.com)
- [Square Enix FFXI NA Page](https://na.finalfantasyxvi.com/)
