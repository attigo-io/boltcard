# Card Privacy

## Brief

The URI that is programmed into the card and returned as the NDEF consists of three parts.
1. The static part
2. The encrypted part
3. The authentication part

```
lnurlw://card.yourdomain.com/ln?p=A2EF40F6D46F1BB36E6EBF0114D4A464&c=F509EEA788E37E32  URI example

lnurlw://card.yourdomain.com/ln?p=                                &c=                  static

                                  A2EF40F6D46F1BB36E6EBF0114D4A464                     encrypted
                             
                                                                     F509EEA788E37E32  authentication
```

| part | use |
|------|-----|
| static | specfying the protocol and service location as a URI |
| encrypted | unique id and counter values encrypted by the card |
| authentication | a value to authenticate that the entire URI is as generated by the card |

## NXP NTAG424DNA features

## Implementation

