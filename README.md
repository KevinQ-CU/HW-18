# HW-18

Info： 

network name:hw18

Node3
Password:3
Public address of the key:   0x540f019EBba5b5c15eFE76f8030bDc4321E62123
Path of the secret key file: node3\keystore\UTC--2020-05-11T01-51-06.165139300Z--540f019ebba5b5c15efe76f8030bdc4321e62123

self=enode://02b76fdd4ca95b0dba8bed69b1e9bf56a5796315e1ed7cfab4da33c319f3083da538a95f12f0216f74065a9a2e63aa98c58d536f8713a929e55d1f0b711b4ae4@127.0.0.1:30303

Start node 3: Commit new mining work:number=1 sealhash=80e078…6160f1 uncles=0 txs=0 gas=0 fees=0 elapsed=1.001ms

Node4
Password:4
Public address of the key:   0x2145d16D7522ECD38d19c164B4078d326190c159
Path of the secret key file: node4\keystore\UTC--2020-05-11T01-51-22.068257900Z--2145d16d7522ecd38d19c164b4078d326190c159
self=enode://cce9738a3d83738e9d85d2e5e386cac8b5cb1f63f3c207b85964c1602d9ab8a2c0947d9ad5ebd366f574497503243bfd070e16d3c5098ff4a802f7b9b9ad318e@127.0.0.1:30304



./geth --datadir node4 --port 30304 --rpc --bootnodes "enode://02b76fdd4ca95b0dba8bed69b1e9bf56a5796315e1ed7cfab4da33c319f3083da538a95f12f0216f74065a9a2e63aa98c58d536f8713a929e55d1f0b711b4ae4@127.0.0.1:30303" --ipcdisable