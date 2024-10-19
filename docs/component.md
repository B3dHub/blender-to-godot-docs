# Component

Create component such as Navmesh, Rigid body etc.

<p><img :src="$withBase('/img/ui_component.png')" alt='' /></p>

---

## Navmesh

Create navigation (-navmesh)

A mesh node with the `-navmesh` suffix will be converted to a navigation mesh. The original Mesh object will be removed at import-time.

[learn more](https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_3d_scenes/node_type_customization.html#create-navigation-navmesh)

---

## Occluder

Create Occluder (-occonly)

If a mesh is imported with the `-occ` suffix an [Occluder3D](https://docs.godotengine.org/en/stable/classes/class_occluder3d.html#class-occluder3d) node will be created based on the geometry of the mesh, it does not replace the mesh. A mesh node with the `-occonly` suffix will be converted to an [Occluder3D](https://docs.godotengine.org/en/stable/classes/class_occluder3d.html#class-occluder3d) on import.

[learn more](https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_3d_scenes/node_type_customization.html#create-occluder-occ-occonly)

---

## Rigid Body

Rigid Body (-rigid)

A mesh node with the `-rigid` suffix will be imported as a [RigidBody3D](https://docs.godotengine.org/en/stable/classes/class_rigidbody3d.html#class-rigidbody3d).

[learn more](https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_3d_scenes/node_type_customization.html#rigid-body-rigid)

---

## Vehicle Body

Create a VehicleBody (-vehicle)

A mesh node with the `-vehicle` suffix will be imported as a child to a [VehicleBody3D](https://docs.godotengine.org/en/stable/classes/class_vehiclebody3d.html#class-vehiclebody3d) node.

[learn more](https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_3d_scenes/node_type_customization.html#create-a-vehiclewheel-wheel)

---

## Vehicle Wheel

Create a VehicleWheel (-wheel)

A mesh node with the `-wheel` suffix will be imported as a child to a [VehicleWheel3D](https://docs.godotengine.org/en/stable/classes/class_vehiclewheel3d.html#class-vehiclewheel3d) node.

[learn more](https://docs.godotengine.org/en/stable/tutorials/assets_pipeline/importing_3d_scenes/node_type_customization.html#create-navigation-navmesh)
