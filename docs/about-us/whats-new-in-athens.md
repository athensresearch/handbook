---
description: >-
  An overview of the features and improvements made to Athens on a monthly
  basis.
---

# What's new in Athens?

### May 2021

{% hint style="info" %}
**Thanks to community member Sawhney for writing the May update!**
{% endhint %}

It's been a month of active development at Athens and there's quite a bit to show for it. A lot of the work this month has been focused on bug fixes, enhancements and performance improvements but we've got a couple of neat features as well. We are seeing the biggest improvement in the short history of Athens in terms of search and block references. While it used to take over 15 seconds on some databases to load, @juniusfree has reduced the time to **instant** even on _huge_ databases. You've got to see it to believe it!

We've also seen improved responsiveness in long pages thanks to @shanberg which has led to an overall more responsive experience.

The list of bug fixes is long \(_yippee_\), we've fixed that pesky little undo redo issue so that your data doesn't disappear between undo and redo \(_thanks Jeff!_\), we've changed some icons and have done quite a bit more!

Lots of improvements have been made to hyperlinks and we've fixed one of the most prominent bugs with the roam import.

Oh yeah, how could I forget, in the "all pages" view, you can now sort pages alphabetically, by created date, by modified date and even by the total links to it. _Pretty neat!_

Here are all of the changes made this month!

#### **Bug Fixes**

* **auto-complete:** pressing \[\[,\(\( and enter works better. close [\#1214](https://github.com/athensresearch/athens/issues/1214), [\#1220](https://github.com/athensresearch/athens/issues/1220) \([\#1219](https://github.com/athensresearch/athens/issues/1219)\) \([856b282](https://github.com/athensresearch/athens/commit/856b282f00a292b206afa5164a8901a15a3a9203)\), closes [\#1204](https://github.com/athensresearch/athens/issues/1204)
* update deps and cljstyle fix \([\#1224](https://github.com/athensresearch/athens/issues/1224)\) \([181ad52](https://github.com/athensresearch/athens/commit/181ad52286d982586a9c1f5016d37553915b6b05)\)
* **undo:** undo after pair character input \([\#1194](https://github.com/athensresearch/athens/issues/1194)\) \([b635da0](https://github.com/athensresearch/athens/commit/b635da00d98c296a533510ef4e47fb021800c75b)\), closes [\#559](https://github.com/athensresearch/athens/issues/559)
* **unlinked-refs:** update unlinked refs when page changes \([\#1195](https://github.com/athensresearch/athens/issues/1195)\) \([5d7b0fe](https://github.com/athensresearch/athens/commit/5d7b0febca5fb9030378857a32fda08f7d876982)\)
* **contentarea:** hide multiline text in contentarea \([\#1189](https://github.com/athensresearch/athens/issues/1189)\) \([dbaa1e5](https://github.com/athensresearch/athens/commit/dbaa1e5138640e2d88a702078e9e1bff408102a7)\)
* **keybindings:** place caret correctly after ctrl-i italics \([\#1176](https://github.com/athensresearch/athens/issues/1176)\) \([a11ea7b](https://github.com/athensresearch/athens/commit/a11ea7b8fc3aff2afccf970658adace05f5c7a13)\)
* **parser:** remove support for underscores so URLs can use \([dd5affb](https://github.com/athensresearch/athens/commit/dd5affb08f1c32efe1917704608bc7380c0df2ae)\)
* **roam-import:** fix roam-date regex to match ordinal numbers in roam dates more \([\#1171](https://github.com/athensresearch/athens/issues/1171)\) \([ebd9aac](https://github.com/athensresearch/athens/commit/ebd9aac89e73f2fb7c97bb79903945410c6fe925)\), closes [\#1135](https://github.com/athensresearch/athens/issues/1135)
* **parser:** add regression test for fixed issue [\#1057](https://github.com/athensresearch/athens/issues/1057) \([\#1175](https://github.com/athensresearch/athens/issues/1175)\) \([e74c0c6](https://github.com/athensresearch/athens/commit/e74c0c6cfe4e4288b7a34ff2588d6d4ae434ddb6)\)
* **keybindings:** redo sometimes does undo \([\#1151](https://github.com/athensresearch/athens/issues/1151)\) \([975afc0](https://github.com/athensresearch/athens/commit/975afc04df3422c8a519ef879a522eb0095a7862)\)
* add cljstyle alias to lein \([\#1132](https://github.com/athensresearch/athens/issues/1132)\) \([a64025a](https://github.com/athensresearch/athens/commit/a64025a3abd9b1ceaa6b1ebd246f06f9f9a79038)\)
* Removal of a daily journal page creates a 404 \([\#1094](https://github.com/athensresearch/athens/issues/1094)\) \([640420f](https://github.com/athensresearch/athens/commit/640420f8fa81ccf88b0a3dc73b55f89949e91a87)\)
* **block-embed:** when block-embed is deleted, render uid instead of "invalid" \([\#1093](https://github.com/athensresearch/athens/issues/1093)\) \([23f1f93](https://github.com/athensresearch/athens/commit/23f1f93453bc090ec6ac4fe1e5562f1183f4365d)\)

#### **Enhancements**

* **ui:** Stop content shift when scrollbars appear/disappear \([\#1212](https://github.com/athensresearch/athens/issues/1212)\) \([9988417](https://github.com/athensresearch/athens/commit/9988417ca3d1298031bfee933366a9969a548910)\)
* **all-pages:** add arrow UI and re-frame constructs \([\#1152](https://github.com/athensresearch/athens/issues/1152)\) \([d59198f](https://github.com/athensresearch/athens/commit/d59198ff7f99d2fb80a35e43231b3dfec560955e)\)
* **daily-notes:** Shorter debounce time for loading of daily pages \([\#1136](https://github.com/athensresearch/athens/issues/1136)\) \([9dca967](https://github.com/athensresearch/athens/commit/9dca967ce1564f9c6c09a46f8d3324b6c9c81585)\)
* **left-sidebar:** clicking on the logo opens to issue creation rather than main repo [\#1130](https://github.com/athensresearch/athens/issues/1130) \([82dd853](https://github.com/athensresearch/athens/commit/82dd853d1f9d253a315f8bc7aadcd9e625300367)\)
* **linked-refs:** sort references by newest first \([\#1124](https://github.com/athensresearch/athens/issues/1124)\) \([19fb97a](https://github.com/athensresearch/athens/commit/19fb97add8e744e24e7d7df3aec2238556cf22da)\), closes [\#728](https://github.com/athensresearch/athens/issues/728)

#### **Documentation**

* Fix grammar in README \([\#1235](https://github.com/athensresearch/athens/issues/1235)\) \([e55f3f8](https://github.com/athensresearch/athens/commit/e55f3f82e328ee6b1ca758ac3bd5491f717680c5)\)

#### **Performance**

* **blocks:** reduce blocks DOM weight \([\#1217](https://github.com/athensresearch/athens/issues/1217)\) \([7b922a5](https://github.com/athensresearch/athens/commit/7b922a523991fd5f59f69422a34feb47a9a6c758)\)
* **right-sidebar:** fix memory+time leak with proper GC of sorted-map [\#1239](https://github.com/athensresearch/athens/issues/1239) \([\#1242](https://github.com/athensresearch/athens/issues/1242)\) \([32d66f5](https://github.com/athensresearch/athens/commit/32d66f5e514531a080454dc337cf7535381865fb)\)
* **search:** faster search for \(\(\)\), \[\[\]\] and ctrl-k \([\#1191](https://github.com/athensresearch/athens/issues/1191)\) \([5cfcb2a](https://github.com/athensresearch/athens/commit/5cfcb2a60bc0a5079690fcfb8674767d1a458720)\), closes [\#756](https://github.com/athensresearch/athens/issues/756) [\#756](https://github.com/athensresearch/athens/issues/756)

#### **Features**

* **app-toolbar:** updated filesystem/sync icons \([\#1146](https://github.com/athensresearch/athens/issues/1146)\) \([e2ba5d7](https://github.com/athensresearch/athens/commit/e2ba5d7f69d8c628df7a86edfd153fb23643a12b)\)
* **datalog-console:** respond to datalog-console messages in browser \([\#1193](https://github.com/athensresearch/athens/issues/1193)\) \([3ffb781](https://github.com/athensresearch/athens/commit/3ffb781fbfc44a37156a9290cd49a1e2ff631beb)\)
* **electron:** set min width and height for electron window \([\#1173](https://github.com/athensresearch/athens/issues/1173)\) \([f41c028](https://github.com/athensresearch/athens/commit/f41c0289357a06c3d6a5ad538eb0c731457606d5)\)
* **keybindings:** keybindings for Graph, All Pages, and Settings \([\#1192](https://github.com/athensresearch/athens/issues/1192)\) \([47efb81](https://github.com/athensresearch/athens/commit/47efb818a02a3e74e6e994337b0e1eb30c83199f)\)
* **all-pages:** allow sort by titles / links / times \([\#1105](https://github.com/athensresearch/athens/issues/1105)\) \([2e6c548](https://github.com/athensresearch/athens/commit/2e6c54865e1a7b78419c639627aebf4cad621695)\)

#### **Dependency Stuff**

* upgrade yarn deps alongside lein deps, fix demo \([\#1246](https://github.com/athensresearch/athens/issues/1246)\) \([c1b6195](https://github.com/athensresearch/athens/commit/c1b619519f1e46bd4f5e9dcae6bf86dac9382b77)\)
* downgrade re-frame-10x so web version works, comment out deps-check \([\#1244](https://github.com/athensresearch/athens/issues/1244)\) \([5fd5763](https://github.com/athensresearch/athens/commit/5fd57630c2bc76efba7c73d6b75cb33524935c52)\)

