# L3S2_ProjetPF

This is one of my last project during my third years of Bachelor's degree . I had to study a calculation model of my choice. I took the Shepherdson–Sturgis register machine introduced in 1963.

The ocaml implementation of our registry machine has two versions with slightly different data structures. The first with a Registry Dictionary and an instruction list. The second with Two dictionaries, one of registry and one of instruction.
---------------------------------------------------------------------------------------------------

_To launch the project:_ 

- Include the file
- Here is a exemple for the first version:
```ocaml
    let test = execution1 division registre;;
```
- An exemple for the second version:
```ocaml
    let test2 = execution2 addition registre2;;
```

--------------------------------------------------------------------------------------------------
That should give you a display of the state of the registers at each call of an instruction.

