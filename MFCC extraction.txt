# Load audio file
x, sr = librosa.load(file_path, sr=44100)

# Compute MFCC
mfcc = librosa.feature.mfcc(y=x, sr=sr)
plt.figure(figsize=(5, 5))  # square for 229x229
librosa.display.specshow(mfcc, sr=sr, cmap='viridis')
plt.axis('off')
plt.tight_layout()

# Save MFCC image
plt.savefig(output_path, bbox_inches='tight', pad_inches=0)
plt.close()
