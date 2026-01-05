## Wan2.2-Animate - Image to Video! Perfect Character Consistency, Animation and Replacement Model

Qwen officially introduces **Wan2.2-Animate-14B**, a unified character animation and replacement model that can fully replicate movements and expressions. Model weights and inference code are publicly available. You can try it on wan.video, ModelScope Studio, or HuggingFace Space!

### Quick Start

**# Clone the repository**

```bash
git clone https://huggingface.co/spaces/Wan-AI/Wan2.2-Animate
cd Wan2.2-Animate
```

**# Create and activate Python environment**

```bash
python -m venv env

# On Windows:
.\env\Scripts\activate.ps1

# On Linux/Mac:
source env/bin/activate
```

**# Install dependencies and run**

```bash
pip install -r requirements.txt
python app.py
```

After successful installation, access the local address: http://127.0.0.1:7860/

### Quantized Model Options

For reduced resource usage, quantized versions of the model are available:

- **HuggingFace Model Repository**: [Wan-AI/Wan2.2-Animate-14B](https://huggingface.co/Wan-AI/Wan2.2-Animate-14B)
- **Quantized variants**: Look for community-created quantized versions on HuggingFace (search for "Wan2.2-Animate GGUF" or "Wan2.2-Animate quantized")
  - ⚠️ **Note**: Verify model authenticity and test performance before production use
- **Recommended for local deployment**: 
  - 4-bit or 8-bit quantization: Recommended for GPUs with 8-16GB VRAM (may have slight quality reduction)
  - GGUF format: For CPU inference or lower VRAM usage
  - Full precision: Requires 24GB+ VRAM (best quality)
  - Actual VRAM usage varies with batch size and resolution settings

**Note**: This web interface uses the DashScope cloud API. For local inference with quantization, refer to the [official GitHub repository](https://github.com/Wan-Video/Wan2.2) for inference code.

![img](README.assets/02d0939ebf20250923222850-scaled-1758853372713-3.webp)
