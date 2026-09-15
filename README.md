# Ziglings

![Ziglings](images/ziglings_dark.jpg "Ziglings")

This repository is my **personal fork of [Ziglings](https://codeberg.org/ziglings/exercises)**, created as a space to **study and practice the [Zig](https://ziglang.org/) programming language**.

The exercises, explanations, and original project structure belong to the maintainers and contributors of **Ziglings**.

**Original project:** [Ziglings](https://codeberg.org/ziglings/exercises)

## What is Ziglings?

**Ziglings** is an educational project made up of a series of small Zig programs that are intentionally incomplete or broken.

Each exercise introduces one or more concepts from the language. The goal is to inspect the code, compile it, understand the compiler errors or unexpected behavior, and then fix the program until it works as expected.

Instead of focusing only on theory, Ziglings encourages learning through practice:

**read the code → compile → understand the error → fix it → run it again**

The compiler messages themselves are part of the learning experience, helping you become familiar with both Zig's syntax and the way the language works.

## Getting started

Ziglings closely follows Zig development and may require a **development build** of the Zig compiler.

This fork is currently being used and tested with:

```text
Zig 0.17.0-dev.2127+e90365cd5
```

Clone this repository and enter the project directory:

```bash
git clone https://github.com/viniciusnevescosta/ziglings ziglings
cd ziglings
```

Then run:

```bash
zig build
```

Ziglings will guide you through the exercises and display the relevant compiler output.

## Useful commands

| Command | Description |
| --- | --- |
| `zig build` | Runs the exercises starting from the next unfinished one |
| `zig build -Dn=19` | Runs a specific exercise |
| `zig build -Ds=27` | Starts from a specific exercise |
| `zig build -Drandom` | Picks a random exercise |
| `zig build -Dreset` | Runs all exercises again |
| `zig build -h` | Shows the available build options |
| `zig run exercises/001_hello.zig` | Runs an exercise directly with the Zig compiler |

## Progress

| Done | # | Exercise |
| :---: | :---: | --- |
| [x] | 001 | [`hello`](exercises/001_hello.zig) |
| [x] | 002 | [`std`](exercises/002_std.zig) |
| [x] | 003 | [`assignment`](exercises/003_assignment.zig) |
| [x] | 004 | [`arrays`](exercises/004_arrays.zig) |
| [x] | 005 | [`arrays2`](exercises/005_arrays2.zig) |
| [x] | 006 | [`strings`](exercises/006_strings.zig) |
| [x] | 007 | [`strings2`](exercises/007_strings2.zig) |
| [x] | 008 | [`quiz`](exercises/008_quiz.zig) |
| [x] | 009 | [`if`](exercises/009_if.zig) |
| [x] | 010 | [`if2`](exercises/010_if2.zig) |
| [x] | 011 | [`while`](exercises/011_while.zig) |
| [x] | 012 | [`while2`](exercises/012_while2.zig) |
| [x] | 013 | [`while3`](exercises/013_while3.zig) |
| [x] | 014 | [`while4`](exercises/014_while4.zig) |
| [x] | 015 | [`for`](exercises/015_for.zig) |
| [x] | 016 | [`for2`](exercises/016_for2.zig) |
| [ ] | 017 | [`quiz2`](exercises/017_quiz2.zig) |
| [ ] | 018 | [`functions`](exercises/018_functions.zig) |
| [ ] | 019 | [`functions2`](exercises/019_functions2.zig) |
| [ ] | 020 | [`quiz3`](exercises/020_quiz3.zig) |
| [ ] | 021 | [`errors`](exercises/021_errors.zig) |
| [ ] | 022 | [`errors2`](exercises/022_errors2.zig) |
| [ ] | 023 | [`errors3`](exercises/023_errors3.zig) |
| [ ] | 024 | [`errors4`](exercises/024_errors4.zig) |
| [ ] | 025 | [`errors5`](exercises/025_errors5.zig) |
| [ ] | 026 | [`hello2`](exercises/026_hello2.zig) |
| [ ] | 027 | [`defer`](exercises/027_defer.zig) |
| [ ] | 028 | [`defer2`](exercises/028_defer2.zig) |
| [ ] | 029 | [`errdefer`](exercises/029_errdefer.zig) |
| [ ] | 030 | [`switch`](exercises/030_switch.zig) |
| [ ] | 031 | [`switch2`](exercises/031_switch2.zig) |
| [ ] | 032 | [`unreachable`](exercises/032_unreachable.zig) |
| [ ] | 033 | [`iferror`](exercises/033_iferror.zig) |
| [ ] | 034 | [`quiz4`](exercises/034_quiz4.zig) |
| [ ] | 035 | [`enums`](exercises/035_enums.zig) |
| [ ] | 036 | [`enums2`](exercises/036_enums2.zig) |
| [ ] | 037 | [`structs`](exercises/037_structs.zig) |
| [ ] | 038 | [`structs2`](exercises/038_structs2.zig) |
| [ ] | 039 | [`pointers`](exercises/039_pointers.zig) |
| [ ] | 040 | [`pointers2`](exercises/040_pointers2.zig) |
| [ ] | 041 | [`pointers3`](exercises/041_pointers3.zig) |
| [ ] | 042 | [`pointers4`](exercises/042_pointers4.zig) |
| [ ] | 043 | [`pointers5`](exercises/043_pointers5.zig) |
| [ ] | 044 | [`quiz5`](exercises/044_quiz5.zig) |
| [ ] | 045 | [`optionals`](exercises/045_optionals.zig) |
| [ ] | 046 | [`optionals2`](exercises/046_optionals2.zig) |
| [ ] | 047 | [`methods`](exercises/047_methods.zig) |
| [ ] | 048 | [`methods2`](exercises/048_methods2.zig) |
| [ ] | 049 | [`quiz6`](exercises/049_quiz6.zig) |
| [ ] | 050 | [`no_value`](exercises/050_no_value.zig) |
| [ ] | 051 | [`values`](exercises/051_values.zig) |
| [ ] | 052 | [`slices`](exercises/052_slices.zig) |
| [ ] | 053 | [`slices2`](exercises/053_slices2.zig) |
| [ ] | 054 | [`manypointers`](exercises/054_manypointers.zig) |
| [ ] | 055 | [`unions`](exercises/055_unions.zig) |
| [ ] | 056 | [`unions2`](exercises/056_unions2.zig) |
| [ ] | 057 | [`unions3`](exercises/057_unions3.zig) |
| [ ] | 058 | [`quiz7`](exercises/058_quiz7.zig) |
| [ ] | 059 | [`integers`](exercises/059_integers.zig) |
| [ ] | 060 | [`floats`](exercises/060_floats.zig) |
| [ ] | 061 | [`coercions`](exercises/061_coercions.zig) |
| [ ] | 062 | [`loop_expressions`](exercises/062_loop_expressions.zig) |
| [ ] | 063 | [`labels`](exercises/063_labels.zig) |
| [ ] | 064 | [`builtins`](exercises/064_builtins.zig) |
| [ ] | 065 | [`builtins2`](exercises/065_builtins2.zig) |
| [ ] | 066 | [`comptime`](exercises/066_comptime.zig) |
| [ ] | 067 | [`comptime2`](exercises/067_comptime2.zig) |
| [ ] | 068 | [`comptime3`](exercises/068_comptime3.zig) |
| [ ] | 069 | [`comptime4`](exercises/069_comptime4.zig) |
| [ ] | 070 | [`comptime5`](exercises/070_comptime5.zig) |
| [ ] | 071 | [`comptime6`](exercises/071_comptime6.zig) |
| [ ] | 072 | [`comptime7`](exercises/072_comptime7.zig) |
| [ ] | 073 | [`comptime8`](exercises/073_comptime8.zig) |
| [ ] | 074 | [`comptime9`](exercises/074_comptime9.zig) |
| [ ] | 075 | [`quiz8`](exercises/075_quiz8.zig) |
| [ ] | 076 | [`sentinels`](exercises/076_sentinels.zig) |
| [ ] | 077 | [`sentinels2`](exercises/077_sentinels2.zig) |
| [ ] | 078 | [`sentinels3`](exercises/078_sentinels3.zig) |
| [ ] | 079 | [`quoted_identifiers`](exercises/079_quoted_identifiers.zig) |
| [ ] | 080 | [`anonymous_structs`](exercises/080_anonymous_structs.zig) |
| [ ] | 081 | [`anonymous_structs2`](exercises/081_anonymous_structs2.zig) |
| [ ] | 082 | [`anonymous_structs3`](exercises/082_anonymous_structs3.zig) |
| [ ] | 083 | [`anonymous_lists`](exercises/083_anonymous_lists.zig) |
| [ ] | 084 | [`interfaces`](exercises/084_interfaces.zig) |
| [ ] | 085 | [`async`](exercises/085_async.zig) |
| [ ] | 086 | [`async2`](exercises/086_async2.zig) |
| [ ] | 087 | [`async3`](exercises/087_async3.zig) |
| [ ] | 088 | [`async4`](exercises/088_async4.zig) |
| [ ] | 089 | [`async5`](exercises/089_async5.zig) |
| [ ] | 090 | [`async6`](exercises/090_async6.zig) |
| [ ] | 091 | [`async7`](exercises/091_async7.zig) |
| [ ] | 092 | [`async8`](exercises/092_async8.zig) |
| [ ] | 093 | [`async9`](exercises/093_async9.zig) |
| [ ] | 094 | [`async10`](exercises/094_async10.zig) |
| [ ] | 095 | [`quiz_async`](exercises/095_quiz_async.zig) |
| [ ] | 096 | [`hello_c`](exercises/096_hello_c.zig) |
| [ ] | 097 | [`c_math`](exercises/097_c_math.zig) |
| [ ] | 098 | [`for3`](exercises/098_for3.zig) |
| [ ] | 099 | [`memory_allocation`](exercises/099_memory_allocation.zig) |
| [ ] | 100 | [`bit_manipulation`](exercises/100_bit_manipulation.zig) |
| [ ] | 101 | [`bit_manipulation2`](exercises/101_bit_manipulation2.zig) |
| [ ] | 102 | [`formatting`](exercises/102_formatting.zig) |
| [ ] | 103 | [`for4`](exercises/103_for4.zig) |
| [ ] | 104 | [`for5`](exercises/104_for5.zig) |
| [ ] | 105 | [`testing`](exercises/105_testing.zig) |
| [ ] | 106 | [`tokenization`](exercises/106_tokenization.zig) |
| [ ] | 107 | [`threading`](exercises/107_threading.zig) |
| [ ] | 108 | [`threading2`](exercises/108_threading2.zig) |
| [ ] | 109 | [`files`](exercises/109_files.zig) |
| [ ] | 110 | [`files2`](exercises/110_files2.zig) |
| [ ] | 111 | [`labeled_switch`](exercises/111_labeled_switch.zig) |
| [ ] | 112 | [`vectors`](exercises/112_vectors.zig) |
| [ ] | 113 | [`quiz9`](exercises/113_quiz9.zig) |
| [ ] | 114 | [`packed`](exercises/114_packed.zig) |
| [ ] | 115 | [`packed2`](exercises/115_packed2.zig) |

## Resources

| Resource | Link |
| --- | --- |
| Ziglings | [codeberg.org/ziglings/exercises](https://codeberg.org/ziglings/exercises) |
| Zig | [ziglang.org](https://ziglang.org/) |
| Zig documentation | [ziglang.org/documentation/master](https://ziglang.org/documentation/master/) |
| Learn Zig | [ziglang.org/learn](https://ziglang.org/learn/) |
| Zig community | [ziglang.org/community](https://ziglang.org/community/) |

