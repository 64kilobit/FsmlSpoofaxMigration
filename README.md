Modified https://github.com/MetaBorgCube/metaborg-calc Spoofax 2.5.0 project

Requirements:
- Spoofax 2.5.0

Working
- Lanugage Definition (syntax/Calc.sdf3)
- Code Generation (trans\codegen\java.str, Spoofax > Transform > Generate Java Fsm)
- Name bindung  (trans\statics\calc.nabl2)
- Unique names (in states, transitions)
- Single initial state

Todo
- get unreachacble states
- get missing states
- ...
- Remove stuff from calc project

Info:
To show scope graph: When Turnstile opened, Spoofax > Analysis > Debug Project scope graph