# motoko-beginer

## use node version 16
```
nvm use 16
```

create project hello world dapp

```
dfx new hello
```

to show path in file explorer
```
explorer.exe .
```


start or run app
```
dfx start

or

 dfx start --clean
```

deploy
```
dfx deploy
```
```
npm init
```
```
npm start
```



# class

in motoko class is called actor

```
import Debug "mo:base/Debug";
actor DBank{
 var currentValue=300;

assigning
currentvalue:= 100;

Debug.print(debug_show(currentValue)
}
```

## let keyword

is constant we csnnot chsnge its vslue

```
let=232
```

## function

```
let id =234890444
public func topUp(){
  currentValue+=1;
Debug.print(debug_show(currentValue));
};
topUp();
```

call aparticular function on a particular canister

```
dfx canister call canister_name function_name '(argument)'
```

## candid ui  1:35:47 

to get canister id
```
dfx canister id __Candid_UI
```

```
http://127.0.0.1.8000/?canisterid=<Candi_ui-canister-identifier>
```


