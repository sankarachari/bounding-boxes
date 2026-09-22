To use Grounding DINO in Python, you can either use the official repository via torch or use the streamlined inference library provided by Roboflow.
Using Roboflow: This is the fastest way to get started. It automatically handles weights, architecture setup, and model loading under the hood.

pip install inference supervision

Method 2: The Native Way (Using the Official GitHub Repo)
If you need complete control over the tensor outputs, pipeline customization, or fine-tuning, you should use the native PyTorch implementation.
1. Install the official repository:
git clone https://github.com
cd GroundingDINO
pip install -e .

3. Download the model weights:
mkdir weights
cd weights
wget -q https://github.com
cd ..

-------------------
