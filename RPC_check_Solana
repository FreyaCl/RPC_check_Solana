use solana_client::rpc_client::RpcClient;

fn main() {
    let url = "https://api.solana.com";
    let client = RpcClient::new(url);

    let blockhash = client.get_recent_blockhash().unwrap();

    println!("Blockhash: {:?}", blockhash);
}
