# @xstate/fsm

## 1.2.0

### Minor Changes

- 61ccfbd: Make `interpret` default for `TEvent` type parameter more strict. It's now `EventObject` instead of `any` and it matches the default on `createMachine`.
