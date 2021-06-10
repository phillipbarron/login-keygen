# Generate a login code based on a one time password key

copies current 2fa code to the clipboard
## usage

* Export your one time password code in your bash profile

```bash
export E2E_TEST_ONE_TIME_PASSWORD_KEY=SOME_SECRET_CODE
```

* link the command (from within the project)

```bash
[yarn|npm] link
```

run from terminal (this should now be available system-wide)

```bash
acode
```


### todo

- allow param passing to support many types
