# Novus-Contract
STACKS:
1) Sway: 





Academygrafía:
1) Platzi - Programación de Contratos Inteligentes con Sway - Camila Ramos https://platzi.com/clases/7266-sway/61406-sway-basics/
Sway: Rust + Solidity
  Inmutable Variables by default but there is a key to mutable
  Defining Functions: "fn"
  Contract Storage (highest point of sway): in Sway you define all storage variables in one visual block in your code. AKA. Storage Variables: for Global & Permanent Variables.
  Namespaced Storage Access: all functions must annotate the storage access it has.
  Program Types:
  Contracts (.sw file) + Libraries + Scripts + Predicates
  ABI - Application Binary Interface: defines function definitions and return types
  Installation: Rust (copy command in terminal) + RustUP ("rustup install stable") + Sway + Warp Terminal + Fuel (Beta1-2 toolchain)

First Sway Project:
Empowered by fuellabs.github.io "The Fuel Book": https://fuelbook.fuel.network/master/quickstart/developer-quickstart.html
Terminal: 1) fuelup show (para ver versiones); 2) mkdir sway-platzi; 3) cd sway-platzi; 4) forc new counter-contract; 5) code .
VSC: 1) Install de VSC extension for sway; 2) en la carpeta src el archivo main.sw: define de type of contract, the storage variables-globals with its types, the abi, the impl 
Build the contract: terminal: cd counter contract, forc build
Create a Wallet: https://github.com/FuelLabs/forc-wallet#forc-wallet Instalarlo + Vincularlo con el Fuelup component + Initialize + Create account + Find address of the wallet "forc wallet list" + Deploy to test + Put the keys + Find the signature
Deploying: 1) Install Forc-wallet to sign and deploy contracts form CLI; 2) Get test tokens; 3) Deploy the contract

Advanced Types:
Structs: grouping of types (example Car with color, wheels, engine...)
Enums: sum types
StorageMap: special type for save key-value pairs inside storage block.
StorageVec: store more than one value in sigle data structure where each value is assigned and index and can only storage values of the same type

Sway Standard Library:
Addres: type-safe wrapper around the primitive b256 type. Never refers to a deployed smart contract.
ContractID: type-safe wrapper around the primitive b256 type. deterministic identifier analogous to a contract`s address in the EVM.
Indentity: type is a enum that allows handle both address & contractID types. Use for access control.
Result: type for returning and propaging error. If it is ok, returning, if not, propaging error.



