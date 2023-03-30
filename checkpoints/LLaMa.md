# Download the checkpoints and tokenizer [LLaMa]

- Full backup: [ipfs://Qmb9y5GCkTG7ZzbBWMu2BXwMkzyCKcUjtEKPpgdZ7GEFKm](https://ipfs.io/ipfs/Qmb9y5GCkTG7ZzbBWMu2BXwMkzyCKcUjtEKPpgdZ7GEFKm) 
- 7B: [ipfs://QmbvdJ7KgvZiyaqHw5QtQxRtUd7pCAdkWWbzuvyKusLGTw](https://ipfs.io/ipfs/QmbvdJ7KgvZiyaqHw5QtQxRtUd7pCAdkWWbzuvyKusLGTw)
- - File size: 13476939516 bytes
- 13B: [ipfs://QmPCfCEERStStjg4kfj3cmCUu1TP7pVQbxdFMwnhpuJtxk](https://ipfs.io/ipfs/QmPCfCEERStStjg4kfj3cmCUu1TP7pVQbxdFMwnhpuJtxk)
- 30B: [ipfs://QmSD8cxm4zvvnD35KKFu8D9VjXAavNoGWemPW1pQ3AF9ZZ](https://ipfs.io/ipfs/QmSD8cxm4zvvnD35KKFu8D9VjXAavNoGWemPW1pQ3AF9ZZ)
- 65B: [ipfs://QmdWH379NQu8XoesA8AFw9nKV2MpGR4KohK7WyugadAKTh](https://ipfs.io/ipfs/QmdWH379NQu8XoesA8AFw9nKV2MpGR4KohK7WyugadAKTh)

You can download normally, or use these commands from the Kubo CLI:
```shell
# Optional: Preload the 7B model. Retrieves the content you don't have yet. Replace with another CID, as needed.
ipfs refs -r QmbvdJ7KgvZiyaqHw5QtQxRtUd7pCAdkWWbzuvyKusLGTw

# Optional: Pin the 7B model. The GC removes old content you don't use, this prevents the model from being GC'd if enabled.
ipfs pin add QmbvdJ7KgvZiyaqHw5QtQxRtUd7pCAdkWWbzuvyKusLGTw

# Download from IPFS and save to disk via CLI:
ipfs get QmbvdJ7KgvZiyaqHw5QtQxRtUd7pCAdkWWbzuvyKusLGTw --output ./7B
```
