# A Hello Work for Zero Knowledge

If you want to run and verify follow the instruccions:

Build i/o files with:

```shell
nargo check
```

Fill in input values for execution in the Prover.toml file. For example:
x = "1"
y = "2"
Prove the valid execution of your Noir program with your preferred proof name, for example p:

```shell
nargo prove p
```

Verify your proof of name p by running:

```shell
nargo verify p
```

If there is an error something nasty will be logged, if finish smoothly instead then everything is fine.
