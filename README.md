# Repro for rules_ts issue 111

This is a repro for https://github.com/aspect-build/rules_ts/issues/111

## Running

1. `pnpm install`
1. `bazel clean`
1. `bazel build //:index`

The build fails.

Now head to the `tsconfig.json` file and uncomment the types and it should now work.
