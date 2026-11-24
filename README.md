# Ganita

Ganita (गणित) is a small Vedic arithmetic library. Its first release provides `वर्ग`, which returns the square of a number.

With a Vedic CLI that supports packages and a published index entry, run `vedic install ganita` in your project. Save this as `main.ved` and run `vedic main.ved`.

```vedic
आवाहन "pkg:ganita";
वद(वर्ग(७));
```

The output is `४९`. The package manifest is `vedic.toml`, and the library entry point is `lib.ved`.
