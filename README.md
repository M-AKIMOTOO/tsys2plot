# Rust
cargo run --release

[package]  
name = "tsys2plot"  
version = "0.1.0"  
edition = "2024"  
rust-version = "1.85"  
authors = ["Masanori AKIMOTO"]  
  
[dependencies]  
rand = "0.8"  
plotters = "0.3.5"  
chrono = "0.4"  
clap = { version = "4.4", features = ["derive"] }  
