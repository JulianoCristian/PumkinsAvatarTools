# VRCAvatarTools
This editor script tool allows you to copy components from existing avatars to new ones, making it much faster to reimport avatars from blender or setup new ones.

Short video example: [Here](https://puu.sh/BZMGY/53e5dad7c3.mp4)

## Supported Components:
- **Transforms** - Can fix broken poses left behind after animating an avatar
- **Dynamic Bones** - Can copy Dynamic Bones from one avatar to another, if the bone and parent names are the same
- **Avatar Descriptors** - Avatar descriptors, their viseme setup, animation override controllers and pipeline IDs
- **Colliders** - Box, Capsule, Sphere and Mesh Colliders

### Not yet supported:
- **Particle Systems**
- **Audio Sorces**
- **Skinned Mesh Rendereds**
- **Some other things I need to decide to add**

To launch the tool go to `Tools > Pumkin > Avatar Tools`

**Important:** Since this is an editor script it needs to be in a folder called `Editor`anywhere in your project.