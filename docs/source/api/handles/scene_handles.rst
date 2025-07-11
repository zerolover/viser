.. This file is automatically generated by generate_handle_docs.py
.. Do not edit manually - run the script to regenerate

Scene Handles
=============

A handle is created for each object that is added to the scene. These can be
used to read and set state, as well as detect clicks.

When a scene node is added to a server (for example, via
:func:`viser.ViserServer.add_frame()`), state is synchronized between all
connected clients. When a scene node is added to a client (for example, via
:func:`viser.ClientHandle.add_frame()`), state is local to a specific client.

The most common attributes to read and write here are
:attr:`viser.SceneNodeHandle.wxyz` and :attr:`viser.SceneNodeHandle.position`.
Each node type also has type-specific attributes that we can read and write.
Many of these are lower-level than their equivalent arguments in factory
methods like :func:`viser.ViserServer.add_frame()` or
:func:`viser.ViserServer.add_image()`.

.. autoclass:: viser.AmbientLightHandle

.. autoclass:: viser.BatchedAxesHandle

.. autoclass:: viser.BatchedGlbHandle

.. autoclass:: viser.BatchedMeshHandle

.. autoclass:: viser.BoxHandle

.. autoclass:: viser.CameraFrustumHandle

.. autoclass:: viser.DirectionalLightHandle

.. autoclass:: viser.FrameHandle

.. autoclass:: viser.GaussianSplatHandle

.. autoclass:: viser.GlbHandle

.. autoclass:: viser.GridHandle

.. autoclass:: viser.Gui3dContainerHandle

.. autoclass:: viser.HemisphereLightHandle

.. autoclass:: viser.IcosphereHandle

.. autoclass:: viser.ImageHandle

.. autoclass:: viser.LabelHandle

.. autoclass:: viser.LineSegmentsHandle

.. autoclass:: viser.MeshHandle

.. autoclass:: viser.MeshSkinnedBoneHandle

.. autoclass:: viser.MeshSkinnedHandle

.. autoclass:: viser.PointCloudHandle

.. autoclass:: viser.PointLightHandle

.. autoclass:: viser.RectAreaLightHandle

.. autoclass:: viser.SceneNodeHandle

.. autoclass:: viser.SplineCatmullRomHandle

.. autoclass:: viser.SplineCubicBezierHandle

.. autoclass:: viser.SpotLightHandle

.. autoclass:: viser.TransformControlsHandle

