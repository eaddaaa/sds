# SDS
Stratos Decentralized Storage

### Build the node from binary
```bash
git clone https://github.com/stratosnet/sds.git
cd sds
git checkout latest
make build
```
then you can find the binary `ppd` under `./target`
the binary can be install to default $GOPTH by  
```bash
make install
```

### How to Run
To start a resource node, go to the root directory for the node or create one folder 
```bash
# create a new folder 
mkdir rsnode
cd rsnode
```

generate configuration file and/or necessary key pairs
```bash
./ppd config
# then follow the steps
```

run a node 
```bash
./ppd start

```

#### register to indexing node



#### activate resource node by staking


#### start mining 




## Contribution

Thank you for considering to help out with the source code! We welcome contributions
from anyone on the internet, and are grateful for even the smallest of fixes!

If you'd like to contribute to SDS(Stratos Decentralized Storage), please fork, fix, commit and send a pull request
for the maintainers to review and merge into the main code base.

Please make sure your contributions adhere to our coding guidelines:

* Code must adhere to the official Go [formatting](https://golang.org/doc/effective_go.html#formatting)
  guidelines (i.e. uses [gofmt](https://golang.org/cmd/gofmt/)).
* Code must be documented adhering to the official Go [commentary](https://golang.org/doc/effective_go.html#commentary)
  guidelines.
* Pull requests need to be based on and opened against the `main` branch.
* Commit messages should be prefixed with the package(s) they modify.
    * E.g. "pp: make trace configs optional"

--- ---

## License

Copyright 2021 Stratos

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the [License](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.