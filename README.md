# Flow Matching for Class-Preserving Local Timbre Control in Drum One-Shot Generation

Anonymous supplementary material for **Flow Matching for Class-Preserving Local Timbre Control in Drum One-Shot Generation**.

This repository contains compact audio examples for local 8D timbre control in drum one-shot generation. Author identities, private corpus paths, participant names, and non-public training data are intentionally omitted.

## Paper Summary

This paper studies local timbre control for drum one-shot generation: changing a desired timbre descriptor, such as brightness or length, while preserving the original drum class. The method uses a flow-matching generator with Class-Anchored Guidance (CAG) and Timbre Proxy Regularization (TPR). CAG separates class preservation from timbre steering during sampling, and TPR encourages the generated latent to follow the requested descriptor target. The examples below provide qualitative listening material for the reference-anchored local control setting used in the paper.

## Overview

- **Task**: local drum timbre control while preserving the original drum class.
- **Classes**: kick, snare, and hi-hat.
- **Controls**: brightness, depth, hardness, roughness, warmth, sharpness, boominess, and length.
- **Examples**: three samples per class, eight descriptor sweeps per sample.
- **Playback order**: each WAV contains five steps ordered by the input values shown in the tables below.

## Audio Examples

The audio examples in this repository are generated with **Flow Matching + CAG + TPR, cfg 2,1**.

Each row shows the five normalized input values and normalized measured output values for the corresponding audio file.

### Kick

#### Kick 01

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/kick/kick-01/brightness.wav) | 0.294, 0.390, 0.486, 0.582, 0.678 | 0.323, 0.394, 0.506, 0.553, 0.649 |
| Depth | [WAV](./audio/kick/kick-01/depth.wav) | 0.435, 0.571, 0.706, 0.841, 0.977 | 0.523, 0.605, 0.723, 0.674, 0.813 |
| Hardness | [WAV](./audio/kick/kick-01/hardness.wav) | 0.338, 0.480, 0.622, 0.764, 0.907 | 0.488, 0.517, 0.587, 0.722, 0.850 |
| Roughness | [WAV](./audio/kick/kick-01/roughness.wav) | 0.408, 0.524, 0.640, 0.756, 0.871 | 0.495, 0.569, 0.576, 0.659, 0.728 |
| Warmth | [WAV](./audio/kick/kick-01/warmth.wav) | 0.534, 0.620, 0.706, 0.792, 0.878 | 0.668, 0.692, 0.736, 0.775, 0.763 |
| Sharpness | [WAV](./audio/kick/kick-01/sharpness.wav) | 0.466, 0.548, 0.631, 0.714, 0.796 | 0.446, 0.505, 0.596, 0.684, 0.725 |
| Boominess | [WAV](./audio/kick/kick-01/boominess.wav) | 0.264, 0.360, 0.456, 0.553, 0.649 | 0.452, 0.469, 0.498, 0.532, 0.570 |
| Length | [WAV](./audio/kick/kick-01/length.wav) | 0.154, 0.365, 0.577, 0.788, 1.000 | 0.305, 0.416, 0.611, 0.795, 0.994 |

#### Kick 02

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/kick/kick-02/brightness.wav) | 0.123, 0.208, 0.294, 0.379, 0.464 | 0.167, 0.176, 0.294, 0.358, 0.403 |
| Depth | [WAV](./audio/kick/kick-02/depth.wav) | 0.466, 0.553, 0.639, 0.725, 0.811 | 0.583, 0.585, 0.651, 0.715, 0.783 |
| Hardness | [WAV](./audio/kick/kick-02/hardness.wav) | 0.389, 0.484, 0.580, 0.675, 0.770 | 0.262, 0.331, 0.427, 0.441, 0.712 |
| Roughness | [WAV](./audio/kick/kick-02/roughness.wav) | 0.000, 0.161, 0.322, 0.483, 0.644 | 0.000, 0.000, 0.441, 0.523, 0.581 |
| Warmth | [WAV](./audio/kick/kick-02/warmth.wav) | 0.541, 0.598, 0.655, 0.713, 0.770 | 0.629, 0.667, 0.690, 0.709, 0.726 |
| Sharpness | [WAV](./audio/kick/kick-02/sharpness.wav) | 0.488, 0.550, 0.612, 0.674, 0.735 | 0.454, 0.456, 0.556, 0.610, 0.632 |
| Boominess | [WAV](./audio/kick/kick-02/boominess.wav) | 0.461, 0.528, 0.594, 0.661, 0.727 | 0.465, 0.510, 0.557, 0.595, 0.655 |
| Length | [WAV](./audio/kick/kick-02/length.wav) | 0.209, 0.352, 0.496, 0.639, 0.782 | 0.260, 0.454, 0.517, 0.647, 0.804 |

#### Kick 03

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/kick/kick-03/brightness.wav) | 0.153, 0.250, 0.347, 0.444, 0.541 | 0.158, 0.185, 0.350, 0.442, 0.554 |
| Depth | [WAV](./audio/kick/kick-03/depth.wav) | 0.527, 0.639, 0.751, 0.863, 0.975 | 0.581, 0.588, 0.779, 0.879, 1.000 |
| Hardness | [WAV](./audio/kick/kick-03/hardness.wav) | 0.314, 0.462, 0.610, 0.757, 0.905 | 0.289, 0.460, 0.594, 0.723, 0.685 |
| Roughness | [WAV](./audio/kick/kick-03/roughness.wav) | 0.187, 0.314, 0.441, 0.567, 0.694 | 0.494, 0.468, 0.491, 0.571, 0.644 |
| Warmth | [WAV](./audio/kick/kick-03/warmth.wav) | 0.568, 0.648, 0.728, 0.808, 0.888 | 0.708, 0.738, 0.715, 0.763, 0.757 |
| Sharpness | [WAV](./audio/kick/kick-03/sharpness.wav) | 0.452, 0.532, 0.613, 0.693, 0.774 | 0.481, 0.573, 0.679, 0.710, 0.749 |
| Boominess | [WAV](./audio/kick/kick-03/boominess.wav) | 0.326, 0.412, 0.499, 0.585, 0.671 | 0.374, 0.412, 0.452, 0.533, 0.642 |
| Length | [WAV](./audio/kick/kick-03/length.wav) | 0.202, 0.401, 0.601, 0.800, 0.999 | 0.290, 0.445, 0.633, 0.798, 1.000 |

### Snare

#### Snare 01

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/snare/snare-01/brightness.wav) | 0.444, 0.516, 0.588, 0.660, 0.733 | 0.412, 0.473, 0.537, 0.607, 0.703 |
| Depth | [WAV](./audio/snare/snare-01/depth.wav) | 0.301, 0.438, 0.576, 0.713, 0.851 | 0.283, 0.381, 0.458, 0.561, 0.690 |
| Hardness | [WAV](./audio/snare/snare-01/hardness.wav) | 0.442, 0.569, 0.696, 0.823, 0.950 | 0.423, 0.470, 0.666, 0.679, 0.798 |
| Roughness | [WAV](./audio/snare/snare-01/roughness.wav) | 0.437, 0.518, 0.598, 0.678, 0.758 | 0.495, 0.574, 0.658, 0.702, 0.731 |
| Warmth | [WAV](./audio/snare/snare-01/warmth.wav) | 0.301, 0.393, 0.485, 0.577, 0.670 | 0.331, 0.445, 0.479, 0.596, 0.602 |
| Sharpness | [WAV](./audio/snare/snare-01/sharpness.wav) | 0.303, 0.396, 0.489, 0.582, 0.675 | 0.250, 0.356, 0.434, 0.532, 0.637 |
| Boominess | [WAV](./audio/snare/snare-01/boominess.wav) | 0.419, 0.509, 0.598, 0.688, 0.777 | 0.428, 0.494, 0.596, 0.665, 0.762 |
| Length | [WAV](./audio/snare/snare-01/length.wav) | 0.001, 0.251, 0.500, 0.750, 0.999 | 0.182, 0.278, 0.540, 0.763, 0.990 |

#### Snare 02

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/snare/snare-02/brightness.wav) | 0.628, 0.686, 0.743, 0.801, 0.859 | 0.612, 0.659, 0.693, 0.772, 0.815 |
| Depth | [WAV](./audio/snare/snare-02/depth.wav) | 0.355, 0.470, 0.586, 0.701, 0.816 | 0.300, 0.426, 0.598, 0.674, 0.752 |
| Hardness | [WAV](./audio/snare/snare-02/hardness.wav) | 0.469, 0.595, 0.721, 0.848, 0.974 | 0.515, 0.595, 0.672, 0.863, 0.850 |
| Roughness | [WAV](./audio/snare/snare-02/roughness.wav) | 0.593, 0.655, 0.716, 0.778, 0.839 | 0.576, 0.603, 0.734, 0.789, 0.827 |
| Warmth | [WAV](./audio/snare/snare-02/warmth.wav) | 0.195, 0.293, 0.391, 0.490, 0.588 | 0.354, 0.410, 0.448, 0.544, 0.646 |
| Sharpness | [WAV](./audio/snare/snare-02/sharpness.wav) | 0.563, 0.628, 0.692, 0.757, 0.822 | 0.537, 0.582, 0.652, 0.745, 0.782 |
| Boominess | [WAV](./audio/snare/snare-02/boominess.wav) | 0.383, 0.483, 0.583, 0.684, 0.784 | 0.450, 0.528, 0.647, 0.717, 0.777 |
| Length | [WAV](./audio/snare/snare-02/length.wav) | 0.064, 0.298, 0.531, 0.765, 0.998 | 0.244, 0.403, 0.598, 0.772, 0.891 |

#### Snare 03

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/snare/snare-03/brightness.wav) | 0.664, 0.725, 0.785, 0.846, 0.907 | 0.625, 0.689, 0.758, 0.828, 0.908 |
| Depth | [WAV](./audio/snare/snare-03/depth.wav) | 0.084, 0.233, 0.382, 0.532, 0.681 | 0.172, 0.210, 0.361, 0.502, 0.576 |
| Hardness | [WAV](./audio/snare/snare-03/hardness.wav) | 0.583, 0.686, 0.789, 0.891, 0.994 | 0.605, 0.641, 0.687, 0.691, 0.693 |
| Roughness | [WAV](./audio/snare/snare-03/roughness.wav) | 0.543, 0.631, 0.719, 0.806, 0.894 | 0.562, 0.643, 0.700, 0.803, 0.846 |
| Warmth | [WAV](./audio/snare/snare-03/warmth.wav) | 0.044, 0.118, 0.193, 0.267, 0.342 | 0.129, 0.160, 0.246, 0.226, 0.276 |
| Sharpness | [WAV](./audio/snare/snare-03/sharpness.wav) | 0.572, 0.636, 0.700, 0.764, 0.828 | 0.541, 0.594, 0.645, 0.698, 0.757 |
| Boominess | [WAV](./audio/snare/snare-03/boominess.wav) | 0.275, 0.401, 0.528, 0.654, 0.781 | 0.408, 0.490, 0.580, 0.682, 0.786 |
| Length | [WAV](./audio/snare/snare-03/length.wav) | 0.064, 0.298, 0.532, 0.766, 1.000 | 0.230, 0.388, 0.556, 0.775, 1.000 |

### Hat

#### Hat 01

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/hat/hat-01/brightness.wav) | 0.899, 0.915, 0.932, 0.949, 0.966 | 0.901, 0.911, 0.925, 0.936, 0.944 |
| Depth | [WAV](./audio/hat/hat-01/depth.wav) | 0.005, 0.098, 0.190, 0.283, 0.376 | 0.065, 0.113, 0.143, 0.498, 0.522 |
| Hardness | [WAV](./audio/hat/hat-01/hardness.wav) | 0.404, 0.540, 0.676, 0.811, 0.947 | 0.461, 0.570, 0.582, 0.584, 0.651 |
| Roughness | [WAV](./audio/hat/hat-01/roughness.wav) | 0.392, 0.464, 0.536, 0.609, 0.681 | 0.404, 0.480, 0.559, 0.590, 0.675 |
| Warmth | [WAV](./audio/hat/hat-01/warmth.wav) | 0.368, 0.446, 0.525, 0.603, 0.681 | 0.447, 0.465, 0.486, 0.503, 0.526 |
| Sharpness | [WAV](./audio/hat/hat-01/sharpness.wav) | 0.759, 0.786, 0.813, 0.841, 0.868 | 0.740, 0.764, 0.789, 0.813, 0.836 |
| Boominess | [WAV](./audio/hat/hat-01/boominess.wav) | 0.079, 0.184, 0.289, 0.394, 0.500 | 0.207, 0.217, 0.246, 0.393, 0.508 |
| Length | [WAV](./audio/hat/hat-01/length.wav) | 0.003, 0.177, 0.351, 0.526, 0.700 | 0.105, 0.249, 0.405, 0.582, 0.707 |

#### Hat 02

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/hat/hat-02/brightness.wav) | 0.916, 0.933, 0.950, 0.967, 0.984 | 0.923, 0.944, 0.960, 0.972, 0.978 |
| Depth | [WAV](./audio/hat/hat-02/depth.wav) | 0.002, 0.054, 0.106, 0.158, 0.210 | 0.080, 0.096, 0.102, 0.110, 0.116 |
| Hardness | [WAV](./audio/hat/hat-02/hardness.wav) | 0.280, 0.422, 0.564, 0.707, 0.849 | 0.367, 0.484, 0.627, 0.759, 0.672 |
| Roughness | [WAV](./audio/hat/hat-02/roughness.wav) | 0.520, 0.607, 0.694, 0.781, 0.868 | 0.587, 0.653, 0.751, 0.804, 0.834 |
| Warmth | [WAV](./audio/hat/hat-02/warmth.wav) | 0.576, 0.637, 0.698, 0.760, 0.821 | 0.581, 0.596, 0.652, 0.681, 0.692 |
| Sharpness | [WAV](./audio/hat/hat-02/sharpness.wav) | 0.908, 0.927, 0.945, 0.964, 0.982 | 0.903, 0.915, 0.926, 0.928, 0.938 |
| Boominess | [WAV](./audio/hat/hat-02/boominess.wav) | 0.059, 0.155, 0.251, 0.347, 0.443 | 0.211, 0.232, 0.308, 0.421, 0.496 |
| Length | [WAV](./audio/hat/hat-02/length.wav) | 0.021, 0.182, 0.343, 0.504, 0.666 | 0.149, 0.283, 0.401, 0.538, 0.672 |

#### Hat 03

| Descriptor | Audio | Input normalized value | Output normalized value |
|---|---|---|---|
| Brightness | [WAV](./audio/hat/hat-03/brightness.wav) | 0.768, 0.795, 0.821, 0.847, 0.874 | 0.781, 0.799, 0.821, 0.845, 0.870 |
| Depth | [WAV](./audio/hat/hat-03/depth.wav) | 0.173, 0.275, 0.376, 0.477, 0.579 | 0.250, 0.333, 0.359, 0.534, 0.531 |
| Hardness | [WAV](./audio/hat/hat-03/hardness.wav) | 0.485, 0.604, 0.724, 0.843, 0.963 | 0.537, 0.604, 0.780, 0.796, 0.861 |
| Roughness | [WAV](./audio/hat/hat-03/roughness.wav) | 0.471, 0.545, 0.619, 0.692, 0.766 | 0.505, 0.561, 0.585, 0.670, 0.748 |
| Warmth | [WAV](./audio/hat/hat-03/warmth.wav) | 0.192, 0.294, 0.396, 0.498, 0.599 | 0.364, 0.364, 0.370, 0.417, 0.504 |
| Sharpness | [WAV](./audio/hat/hat-03/sharpness.wav) | 0.569, 0.606, 0.642, 0.679, 0.716 | 0.542, 0.575, 0.611, 0.649, 0.695 |
| Boominess | [WAV](./audio/hat/hat-03/boominess.wav) | 0.333, 0.420, 0.508, 0.595, 0.683 | 0.396, 0.454, 0.532, 0.607, 0.673 |
| Length | [WAV](./audio/hat/hat-03/length.wav) | 0.003, 0.173, 0.343, 0.512, 0.682 | 0.194, 0.241, 0.409, 0.507, 0.665 |
