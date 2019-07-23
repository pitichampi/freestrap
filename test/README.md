> Use a real Mardown viewer to read this file… Github online md reader sucks...


*Note : This test directory is sometimes published on freenet. Last known known URI : USK@VBN7rWNotd2F9k10ojHpURHlopTCITKNh~FhmgHmfWo,hexhWQmqwpSXJw~ndvX0MBupkv7FpuQi-Fp7Uh4X8~A,AQACAAE/test/-1/* 

## Tests :

| Item tested  | Test done[^1] | Status[^2]     |
| ------------ | ------------- | --------------- |
| *            | :green_heart: | :ok:            |
| E            | :green_heart: | :ok:            |
| E F          | :green_heart: | :ok:            |
| E > F        | :red_circle:  | :grey_question: |
| :first-child | :green_heart: | :ok:            |
| :active      | :green_heart: | :ok:            |
| :hover       | :green_heart: | :ok:            |
| :focus       | :green_heart: | :ok:            |
| :lang        | :red_circle:  | :grey_question: |
| [foo]        | :green_heart: | :wavy_dash: [^3] |
| [foo="val"]        |  :green_heart:  | :wavy_dash: [^3] |
| [foo~="val"]        |  :green_heart: | :no_entry_sign: |
| :before        |  :green_heart: | :no_entry_sign: |
| :after       |  :green_heart: | :no_entry_sign: |
| :first-letter       |  :green_heart: | :ok:   |
| :first-line        |  :green_heart: | :ok:   |
|              |               |                  |

## Notes :

[^1]: Legend  💚 : tested, :red_circle: : not tested yet
[^2]: Legend  :ok: : working, :no_entry_sign: : not working, :wavy_dash: : working in some cases,  ​❔ : unknown​
[^3]: Working with "href" attr. Tested with some other attributes like "data-attr", doesn't work.

