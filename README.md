# dual-engine-attention
Vectorized, compile-safe Dual-Engine Attention Projector for long-context and quantized Transformers. Replaces softmax with a volume-normalized self-regulating floor driven by an autonomic Effective Dimension (d_{\text{eff}}) control loop to prevent gradient underflow and attention collapse.
