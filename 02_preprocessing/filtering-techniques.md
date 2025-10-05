# Teknik Preprocessing EMG

## Filtering
- **Bandpass Filter**: 20–450 Hz
- **Notch Filter**: 50/60 Hz untuk noise listrik
- **Moving Average**: Untuk smoothing sinyal

## Segmentasi
- Windowing: 200 ms sliding window
- Thresholding: Berdasarkan RMS atau amplitude

## Tools
- SciPy, NumPy, MNE-Python
