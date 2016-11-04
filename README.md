# purescript-erl-tuples
Bindings to native Erlang tuples

Given an Erlang tuple `{42, "foo", true}` represent this directly as `Erl.Data.Tuple.Tuple3 Int String Boolean`. Create a tuple via `tuple3 :: a -> b -> c -> Tuple3 a b c`. Consume via `uncurry3` or to pattern match, convert to `Data.Tuple.Nested` with `toNested3`.
