# `ManifoldTransforms`

<dl>
<dt><a href="./Elements">Elements/</a></dt>
<dd>This directory contains the finite elements:
  <ul> 
    <li><a href="./Elements/GeomWrap3dFrm.m"><code>GeomWrap3dFrm</code></a> Wrapper for 3d frame elements. This element
       implements the <em>element wrapper</em> from Section 6 using Algorithm 1
       from Section 4.
    </li>
    <li><a href="./Elements/GeomTran3dFrm.m"><code>GeomTran3dFrm</code></a> Wrapper for 3d frame elements
       that are formulated in a <em>basic</em> coordinate system. This element
       implements the <em>element wrapper</em> from Section 6 using Algorithm 1
       from Section 4.
    </li>
    <li><a href="./Elements/DisplShear3dFrm_wCS.m"><code>DisplShear3dFrm_wCS</code></a> 
       Displacement-interpolated shear 3d frame element with Cosserat strains; 
       this element implements the three formulations of Appendix B.
    </li>
  </ul>
</dd>
<dt><a href="./Geometry">Geometry/</a></dt>
<dd>
  <ul>
    <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/GeomTran3dFrm_Pull.m"><code>GeomTran3dFrm_Pull</code></a>
    This function implements the $g$ operation of the geometric transformations by calling the following functions:
    <ul>
      <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/Transform_RotPull.m"><code>Transform_RotPull</code></a></li>
      <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/Transform_IsoPull.m"><code>Transform_IsoPull</code></a></li>
      <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/Tran3dFrm_IsoPull.m"><code>Tran3dFrm_IsoPull</code></a></li>
    </ul>
    </li>
    <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/GeomTran3dFrm_Push.m"><code>GeomTran3dFrm_Push</code></a>
    This function implements the $\mathbf{a}_g$ and $\mathbf{k}_g$ operations of the geometric transformations.
    <ul>
      <li><a href="/claudioperez/FiniteRotationLab/blob/master/Geometry/Tran3dFrm_IsoPush.m"><code>Tran3dFrm_IsoPush</code></a></li>
    </ul>
    </li>
  </ul>
</dd>
<dt><a href="./Examples">Examples/</a></dt>
<dd>
  This directory contains scripts to reproduce the examples of the paper.
  <ol>
  <li><a href="./Examples/E10_Invariance.m">Invariance</a></li>
  <li><ol>
      <li><a href="./Examples/E21_PlaneMoment.m">Plane Cantilever - Point moment</a></li>
      <li><a href="./Examples/E22_PlaneTransverse.m">Plane Cantilever - Transverse Force</a></li>
  </ol></li>
  <li><a href="./Examples/E30_HelicalForms.m">Space Cantilever - Point moment and force</a></li>
  <li><a href="./Examples/E40_BatheCantilever.m">Curved Cantilever - Point force (Bathe's problem)</a></li>
  <li><a href="./Examples/E50_Hockling.m">Hockling of a flexible rod.</a></li>
  </ol>
</dd>
For an example using "basic" elements, see <a href="./Examples/E00_Column.m"><code>E00_Column</code></a>.
<dt><a href="./Rotations">Rotations/</a></dt>
<dd>This directory contains the rotation functions described in Appendix A.
</dd>

</dl>


