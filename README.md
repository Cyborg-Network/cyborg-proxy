
<h1 align="center">
  <br>
  <a href="http://www.cyborgnetwork.io"><img src="https://github.com/user-attachments/assets/16067543-6de0-4f62-9a03-d82da38f001a" width="200"></a>
  <br>
  Cyborg Proxy
  <br>
</h1>

<h4 align="center">A proxy that relays usage metrics, specs and logs between <a href="https://github.com/Cyborg-Network/cyborg-connect" target="_blank">Cyborg Connect</a> and <a href="https://github.com/Cyborg-Network/Cyborg-worker-node" target="_blank">Cyborg Miners</a>.</h4>

## Key Features

* Metric Relay - Facilitates usage tracking of <a href="https://github.com/Cyborg-Network/Cyborg-worker-node" target="_blank">Cyborg Miners</a>.
* Spec Relay - Facilitates spec lookup of <a href="https://github.com/Cyborg-Network/Cyborg-worker-node" target="_blank">Cyborg Miners</a>.
* Log Relay - Facilitates log retrieval of <a href="https://github.com/Cyborg-Network/Cyborg-worker-node" target="_blank">Cyborg Miners</a>.
* Health Relay - Facilitates health checking of <a href="https://github.com/Cyborg-Network/Cyborg-worker-node" target="_blank">Cyborg Miners</a>.


## How To Use

To build and run this application you will need to have the rust toolchain installed:

```bash
# Clone this repository
$ git clone https://github.com/Cyborg-Network/cyborg-proxy

# Go into the repository
$ cd cyborg-proxy

# Build the project
$ cargo build --release

# Run the app
$ ./target/release/cyborg-proxy
```
