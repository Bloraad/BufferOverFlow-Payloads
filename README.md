# Check the files
> (spk) fuzz.spk
```
s_readline();
s_string("TRUN ");
s_string_variable("Bloraad");
```
> then execute the command
` generic_send_tcp <ip> <port> fuzz.spk 0 0  `
