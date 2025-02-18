# Nexus Prover Node
You earn NEX Points by contributing compute and interacting with the Nexus ecosystem.

## Contribute via CLI
### 1. Install Dependecies
```bash
sudo apt update & sudo apt upgrade -y
sudo apt install screen curl libssl-dev pkg-config build-essential git-all protobuf-compiler -y
sudo apt update
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```bash
source $HOME/.cargo/env
```

---

### 2. Run Prover
**1- Start a screen to keep it running in the background**
```bash
screen -S nexus
```
**2- Install and run prover**
```bash
curl https://cli.nexus.xyz/ | sh
```
> To minimze the screen: `CTRL+A+D`
>
> To return to screen: `screen -r nexus`
>
> To kill screen: `screen -XS nexus quit`

**3- There will be `prover-id` file in `/root/.nexus` directory**
*Best way to access files on VPS is using Mobaxterm or Termius client to connect to them*

---

### 3. Create account
* Create an account at https://app.nexus.xyz.

* Follow the account linking instructions and link your `prover-id`

* Your contributions will earn NEX Points.

* Track your progress on the leaderboard.

* Manage all your nodes in one place.

---

### Can I use multiple devices?
Yes, you can connect as many devices as you want, including desktops, laptops, mobile phones, and servers. You can link and manage all your devices from a single Nexus account. You can also prove computations in multiple browser tabs simultaneously.
