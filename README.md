# LAYERS-UNITY

public LayerMask layerMask = 1 << 0; // default layer (0)
public LayerMask layerMask2 = ~0; // everything
public LayerMask layerMask2b = -1; // everything
public LayerMask layerMask3 = default;// nothing
public LayerMask layerMask4 = 0;// nothing
public LayerMask layerMask4b; // nothing
public LayerMask layerMask5 = 1 << 5;// layer 5 (UI)
public LayerMask layerMask6 = 1 << 2 | 1 << 5;// Ignore Raycast (Layer 2) AND UI (Layer 5)
public LayerMask layerMask7 = ~(1 << 4 | 1 << 5); // all except layer 4 and 5
public LayerMask layerMask8 = ~(1 << 4); // all except layer 4
