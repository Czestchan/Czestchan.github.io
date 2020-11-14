[TOC]

# Hi

testing

$\hat{H}\Psi=E\Psi $

- Wow

| w    | a    | 1    |
| ---- | ---- | ---- |
| 1    | 2    | sa   |
| 2    | 3    | 33   |
| 2    | 3    | 3    |

```Python
import pytorch as torch
```

## OK

<html>

<head>
<script src="https://3Dmol.csb.pitt.edu/build/3Dmol-min.js"></script>
</head>
<div id="container-01" class="mol-container">
</div>
<style>
.mol-container {
  width: 60%;
  height: 400px;
  position: relative;
}
</style>
<script>
$(function() {
	let element = $('#container-01');
	let config = { backgroundColor : 'white' };
	let viewer = $3Dmol.createViewer( element, config );
	viewer.addModel("CRYST1   11.746   11.746   20.024  90.00  90.00 120.00 P 1\nMODEL     1\nATOM      1   Ni MOL     1       2.644   0.700   6.699  1.00  0.00          NI  \nATOM      2   Ni MOL     1       2.064   3.756   6.699  1.00  0.00          NI  \nATOM      3   Ni MOL     1      -0.872   2.730   6.699  1.00  0.00          NI  \nATOM      4   Ni MOL     1      -1.874   4.465   5.024  1.00  0.00          NI  \nATOM      5   Ni MOL     1       1.063   2.021   5.024  1.00  0.00          NI  \nATOM      6   Ni MOL     1       4.648   0.700   5.024  1.00  0.00          NI  \nATOM      7   Ni MOL     1      -0.293   5.786   6.699  1.00  0.00          NI  \nATOM      8   Ni MOL     1      -0.872   8.842   6.699  1.00  0.00          NI  \nATOM      9   Ni MOL     1      -3.808   7.816   6.699  1.00  0.00          NI  \nATOM     10   Ni MOL     1      -4.810   9.551   5.024  1.00  0.00          NI  \nATOM     11   Ni MOL     1      -1.874   7.107   5.024  1.00  0.00          NI  \nATOM     12   Ni MOL     1       1.711   5.786   5.024  1.00  0.00          NI  \nATOM     13   Ni MOL     1       8.517   0.700   6.699  1.00  0.00          NI  \nATOM     14   Ni MOL     1       7.937   3.756   6.699  1.00  0.00          NI  \nATOM     15   Ni MOL     1       5.001   2.730   6.699  1.00  0.00          NI  \nATOM     16   Ni MOL     1       3.999   4.465   5.024  1.00  0.00          NI  \nATOM     17   Ni MOL     1       6.935   2.021   5.024  1.00  0.00          NI  \nATOM     18   Ni MOL     1      10.520   0.700   5.024  1.00  0.00          NI  \nATOM     19   Ni MOL     1       5.580   5.786   6.699  1.00  0.00          NI  \nATOM     20   Ni MOL     1       5.001   8.842   6.699  1.00  0.00          NI  \nATOM     21   Ni MOL     1       2.064   7.816   6.699  1.00  0.00          NI  \nATOM     22   Ni MOL     1       1.063   9.551   5.024  1.00  0.00          NI  \nATOM     23   Ni MOL     1       3.999   7.107   5.024  1.00  0.00          NI  \nATOM     24   Ni MOL     1       7.584   5.786   5.024  1.00  0.00          NI  \nATOM     25    P MOL     1       0.300   0.700   6.699  1.00  0.00           P  \nATOM     26    P MOL     1       3.236   2.395   5.024  1.00  0.00           P  \nATOM     27    P MOL     1       0.300   4.091   5.024  1.00  0.00           P  \nATOM     28    P MOL     1      -2.636   5.786   6.699  1.00  0.00           P  \nATOM     29    P MOL     1       0.300   7.481   5.024  1.00  0.00           P  \nATOM     30    P MOL     1      -2.636   9.177   5.024  1.00  0.00           P  \nATOM     31    P MOL     1       6.173   0.700   6.699  1.00  0.00           P  \nATOM     32    P MOL     1       9.109   2.395   5.024  1.00  0.00           P  \nATOM     33    P MOL     1       6.173   4.091   5.024  1.00  0.00           P  \nATOM     34    P MOL     1       3.236   5.786   6.699  1.00  0.00           P  \nATOM     35    P MOL     1       6.173   7.481   5.024  1.00  0.00           P  \nATOM     36    P MOL     1       3.236   9.177   5.024  1.00  0.00           P  \nATOM     37   Ni MOL     1      -1.876   4.469   8.297  1.00  0.00          NI  \nATOM     38   Ni MOL     1       1.061   2.017   8.298  1.00  0.00          NI  \nATOM     39   Ni MOL     1       4.652   0.700   8.297  1.00  0.00          NI  \nATOM     40   Ni MOL     1      -4.813   9.555   8.297  1.00  0.00          NI  \nATOM     41   Ni MOL     1      -1.876   7.103   8.298  1.00  0.00          NI  \nATOM     42   Ni MOL     1       1.715   5.786   8.297  1.00  0.00          NI  \nATOM     43   Ni MOL     1       3.997   4.468   8.298  1.00  0.00          NI  \nATOM     44   Ni MOL     1       6.933   2.017   8.298  1.00  0.00          NI  \nATOM     45   Ni MOL     1      10.524   0.700   8.297  1.00  0.00          NI  \nATOM     46   Ni MOL     1       1.061   9.554   8.297  1.00  0.00          NI  \nATOM     47   Ni MOL     1       3.997   7.103   8.298  1.00  0.00          NI  \nATOM     48   Ni MOL     1       7.588   5.786   8.297  1.00  0.00          NI  \nATOM     49    P MOL     1       3.236   2.395   8.430  1.00  0.00           P  \nATOM     50    P MOL     1       0.300   4.090   8.430  1.00  0.00           P  \nATOM     51    P MOL     1       0.300   7.481   8.430  1.00  0.00           P  \nATOM     52    P MOL     1      -2.636   9.176   8.429  1.00  0.00           P  \nATOM     53    P MOL     1       9.109   2.395   8.430  1.00  0.00           P  \nATOM     54    P MOL     1       6.173   4.090   8.429  1.00  0.00           P  \nATOM     55    P MOL     1       6.172   7.481   8.430  1.00  0.00           P  \nATOM     56    P MOL     1       3.236   9.177   8.430  1.00  0.00           P  \nATOM     57   Ni MOL     1       2.550   0.700   9.744  1.00  0.00          NI  \nATOM     58   Ni MOL     1       2.111   3.837   9.745  1.00  0.00          NI  \nATOM     59   Ni MOL     1      -0.825   2.648   9.745  1.00  0.00          NI  \nATOM     60   Ni MOL     1      -0.386   5.786   9.745  1.00  0.00          NI  \nATOM     61   Ni MOL     1      -0.825   8.923   9.745  1.00  0.00          NI  \nATOM     62   Ni MOL     1      -3.762   7.734   9.745  1.00  0.00          NI  \nATOM     63   Ni MOL     1       8.423   0.700   9.745  1.00  0.00          NI  \nATOM     64   Ni MOL     1       7.984   3.837   9.745  1.00  0.00          NI  \nATOM     65   Ni MOL     1       5.048   2.649   9.745  1.00  0.00          NI  \nATOM     66   Ni MOL     1       5.487   5.786   9.745  1.00  0.00          NI  \nATOM     67   Ni MOL     1       5.047   8.923   9.745  1.00  0.00          NI  \nATOM     68   Ni MOL     1       2.111   7.735   9.745  1.00  0.00          NI  \nATOM     69    P MOL     1       0.300   0.699  10.120  1.00  0.00           P  \nATOM     70    P MOL     1      -2.637   5.785  10.120  1.00  0.00           P  \nATOM     71    P MOL     1       6.172   0.699  10.120  1.00  0.00           P  \nATOM     72    P MOL     1       3.236   5.785  10.120  1.00  0.00           P  \nENDMDL\n", "pdb");
	viewer.addUnitCell();
	viewer.setStyle({}, {sphere : {}});
	viewer.render();
});
</script>
<html>