# BDD Billing

A suggested method of charging for Behaviour Driven Development.

```
elicit features from project scope

while ( features on backlog ) {
    select features for next release
    create aceptance criteria for features
    charge time

    if ( quote required for next release ) {
        quote for release

        if ( quote rejected and no resolution ) {
            client takes aceptance criteria to another Agile team
        }

        if ( quote accepted ) {
            develop, test and release features
            charge quote value
        }

    } else {
       develop, test and release features
       charge time
    }
}
```

### Advantages
* Gives the client a choice of pay-for-release or pay-for-time.
* Always leaves client with useful output at the end of each iteration.
