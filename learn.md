- continue the update the solnaa program of anchor.toml file

```bash
rm ./target/idl/solana_program.json

anchor keys list

//keys sync will updated with new one program address
anchor keys sync

anchor build
```

```bash
// it will create new solana new wallet json
solana-keygen new -o id.json
```

Wallet address :
- EJpJc3KYwZXtH8YEFSJoJiLT4WkcFSkkWomygbWtgWi1


```bash


solana balance payer.json


anchor deploy

```


> //After deploying the program we will get the program id
   Dk6jEcX41441XG58ifP25zBVwPTvhbe4Rhc8pZpxVzbM

//Signature of the deployed program
5h2XhA7tXUYGcWQuv936kA82kQZRuzrMFB3c6GLi2ZCdtWQb9yqQ3dCtcUoAyCcZ39mP98y8Qppjts4j2iWN39LS

