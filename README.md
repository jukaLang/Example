# Example
Example of Juka Library that can be installed by Juka

## Download it in Juka:

### Inside Juka REPL
Press "Install a Package" and type jukaLang


## Running inside Juka Code/File:

```jsx
get @jukaLang/Example/main.juk
```

Example:
```jsx
func main() = {
   // Running Juka Code
   printLine("Starting to run Example");
   get example = @jukaLang/Example/main.juk
   example.main();
}
```
