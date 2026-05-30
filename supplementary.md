# Supplementary Material

## Supplementary Table S1



````{raw:typst}
#let tableStyle = (
  map-cells: cell => {
    cell.content = {
      set text(size: 7pt)
      cell.content
    }
    cell
  }
)

#show figure.where(kind: "table"): it => context {
  set text(size: 7pt)

  let m = page.margin
  let left = if type(m) == dictionary {
    if "left" in m { m.left }
    else if "x" in m { m.x }
    else { 0pt }
  } else if type(m) == length {
    m
  } else {
    0pt
  }

  pad(left: -left, it)
}
````

```{list-table} Top 50 unique functional network connections for faces.
:header-rows: 1
:name: tbl-face-connections

* - Rank
  - Region 1
  - Network 1
  - Region 2
  - Network 2
  - Direction
  - t-value
  - |t|

* - 1
  - Left Visual Area 3CD
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -14.547
  - 14.547

* - 2
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -13.995
  - 13.995

* - 3
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -12.298
  - 12.298

* - 4
  - Left Visual Area 3CD
  - Visual2
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -11.867
  - 11.867

* - 5
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -11.351
  - 11.351

* - 6
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -11.172
  - 11.172

* - 7
  - Left Parahippocampal
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -11.092
  - 11.092

* - 8
  - Left Visual Area 4
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -11.078
  - 11.078

* - 9
  - Right Visual Area 4
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.984
  - 10.984

* - 10
  - Left Parahippocampal
  - Visual2
  - Right Fusiform Face Complex
  - Visual2
  - Negative
  - -10.972
  - 10.972

* - 11
  - Left Intraparietal 2
  - Frontoparietal
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.934
  - 10.934

* - 12
  - Left Visual Area 4 Transitional
  - Visual2
  - Right Visual Area 4
  - Visual2
  - Negative
  - -10.872
  - 10.872

* - 13
  - Left Visual Area 3B
  - Visual2
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -10.775
  - 10.775

* - 14
  - Left Intraparietal 2
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -10.765
  - 10.765

* - 15
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Left Parahippocampal
  - Visual2
  - Negative
  - -10.750
  - 10.750

* - 16
  - Right Intraparietal 2
  - Frontoparietal
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.702
  - 10.702

* - 17
  - Left Posterior Inferotemporal
  - Visual2
  - Right Parahippocampal
  - Visual2
  - Negative
  - -10.699
  - 10.699

* - 18
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.678
  - 10.678

* - 19
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -10.677
  - 10.677

* - 20
  - Left Posterior Inferotemporal
  - Visual2
  - Left Parahippocampal
  - Visual2
  - Negative
  - -10.624
  - 10.624

* - 21
  - Left Primary Visual Cortex
  - Visual1
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -10.623
  - 10.623

* - 22
  - Left Parahippocampal
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.588
  - 10.588

* - 23
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Left Visual Area 3CD
  - Visual2
  - Negative
  - -10.558
  - 10.558

* - 24
  - Left Area p9-46v
  - Frontoparietal
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.546
  - 10.546

* - 25
  - Left Fusiform Face Complex
  - Visual2
  - Left Parahippocampal
  - Visual2
  - Negative
  - -10.518
  - 10.518

* - 26
  - Left Parahippocampal
  - Visual2
  - Right Posterior Inferotemporal
  - Visual2
  - Negative
  - -10.505
  - 10.505

* - 27
  - Left Intraparietal 1
  - Frontoparietal
  - Right Primary Visual Cortex
  - Visual1
  - Negative
  - -10.483
  - 10.483

* - 28
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8C
  - Frontoparietal
  - Negative
  - -10.448
  - 10.448

* - 29
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -10.416
  - 10.416

* - 30
  - Left Intraparietal 2
  - Frontoparietal
  - Left Visual Area 3CD
  - Visual2
  - Negative
  - -10.415
  - 10.415

* - 31
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Premotor 6a
  - Dorsal-attention
  - Negative
  - -10.392
  - 10.392

* - 32
  - Left Parahippocampal
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -10.312
  - 10.312

* - 33
  - Left Intraparietal 2
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.302
  - 10.302

* - 34
  - Left Visual Area 4
  - Visual2
  - Left Parahippocampal
  - Visual2
  - Negative
  - -10.295
  - 10.295

* - 35
  - Right Intraparietal 1
  - Frontoparietal
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.288
  - 10.288

* - 36
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Premotor 6a
  - Dorsal-attention
  - Negative
  - -10.287
  - 10.287

* - 37
  - Left Primary Visual Cortex
  - Visual1
  - Left Intraparietal 2
  - Frontoparietal
  - Negative
  - -10.264
  - 10.264

* - 38
  - Left Visual Area 3B
  - Visual2
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Negative
  - -10.253
  - 10.253

* - 39
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Right Secondary Visual Cortex
  - Visual2
  - Negative
  - -10.231
  - 10.231

* - 40
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -10.212
  - 10.212

* - 41
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Right Dorsal Visual Temporal
  - Visual1
  - Negative
  - -10.145
  - 10.145

* - 42
  - Left Visual Area 4 Transitional
  - Visual2
  - Right Primary Visual Cortex
  - Visual1
  - Negative
  - -10.135
  - 10.135

* - 43
  - Right Visual Area 4
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -10.125
  - 10.125

* - 44
  - Left Intraparietal 1
  - Frontoparietal
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -10.123
  - 10.123

* - 45
  - Left Visual Area 3CD
  - Visual2
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -10.092
  - 10.092

* - 46
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Prefrontal Medial
  - Frontoparietal
  - Negative
  - -9.987
  - 9.987

* - 47
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Right Visual Area 3A
  - Visual2
  - Negative
  - -9.969
  - 9.969

* - 48
  - Left Area p9-46v
  - Frontoparietal
  - Left Visual Area 3CD
  - Visual2
  - Negative
  - -9.960
  - 9.960

* - 49
  - Left Visual Area 4
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -9.929
  - 9.929

* - 50
  - Left Area p9-46v
  - Frontoparietal
  - Right Visual Area 3
  - Visual2
  - Negative
  - -9.865
  - 9.865

```

## Supplementary Table S2

```{list-table} Top 50 unique functional network connections for bodies.
:header-rows: 1
:name: tbl-body-connections

* - Rank
  - Region 1
  - Network 1
  - Region 2
  - Network 2
  - Direction
  - t-value
  - |t|

* - 1
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -14.132
  - 14.132

* - 2
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -14.055
  - 14.055

* - 3
  - Left Medial Intraparietal
  - Dorsal-attention
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -13.230
  - 13.230

* - 4
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Right Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -12.744
  - 12.744

* - 5
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -12.664
  - 12.664

* - 6
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -12.651
  - 12.651

* - 7
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -12.589
  - 12.589

* - 8
  - Right Dorsal Visual Temporal
  - Visual1
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -12.398
  - 12.398

* - 9
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -12.332
  - 12.332

* - 10
  - Left Intraparietal 1
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -12.248
  - 12.248

* - 11
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -12.196
  - 12.196

* - 12
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -12.050
  - 12.050

* - 13
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -12.048
  - 12.048

* - 14
  - Left Visual Area 3B
  - Visual2
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -12.029
  - 12.029

* - 15
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -11.989
  - 11.989

* - 16
  - Left Visual Area 3CD
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -11.818
  - 11.818

* - 17
  - Right Visual Area 3B
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -11.790
  - 11.790

* - 18
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -11.756
  - 11.756

* - 19
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -11.750
  - 11.750

* - 20
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -11.696
  - 11.696

* - 21
  - Left Dorsal Visual Temporal
  - Visual1
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -11.610
  - 11.610

* - 22
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Right Dorsal Visual Temporal
  - Visual1
  - Negative
  - -11.605
  - 11.605

* - 23
  - Right Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -11.484
  - 11.484

* - 24
  - Left Intraparietal 2
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -11.446
  - 11.446

* - 25
  - Left Parahippocampal
  - Visual2
  - Right Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -11.388
  - 11.388

* - 26
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - L_i6-8
  - Frontoparietal
  - Negative
  - -11.275
  - 11.275

* - 27
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -11.273
  - 11.273

* - 28
  - Left Intraparietal 1
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -11.235
  - 11.235

* - 29
  - Right Premotor 6a
  - Dorsal-attention
  - Right Dorsal Visual Temporal
  - Visual1
  - Negative
  - -11.215
  - 11.215

* - 30
  - Left Dorsal Visual Temporal
  - Visual1
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -11.186
  - 11.186

* - 31
  - Left Medial Intraparietal
  - Dorsal-attention
  - Right Inferior Frontal Sulcus Posterior
  - Frontoparietal
  - Negative
  - -11.169
  - 11.169

* - 32
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Inferior Frontal Sulcus Posterior
  - Frontoparietal
  - Negative
  - -11.164
  - 11.164

* - 33
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -11.130
  - 11.130

* - 34
  - Left Intraparietal 1
  - Frontoparietal
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -11.119
  - 11.119

* - 35
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -11.099
  - 11.099

* - 36
  - Right Area p9-46v
  - Frontoparietal
  - Right Dorsal Visual Temporal
  - Visual1
  - Negative
  - -10.994
  - 10.994

* - 37
  - Left Intraparietal Sulcus 1
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.982
  - 10.982

* - 38
  - Left Inferior Frontal Sulcus Anterior
  - Frontoparietal
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -10.888
  - 10.888

* - 39
  - Left Parahippocampal
  - Visual2
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.877
  - 10.877

* - 40
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.858
  - 10.858

* - 41
  - Left Intraparietal 1
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.857
  - 10.857

* - 42
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8C
  - Frontoparietal
  - Negative
  - -10.760
  - 10.760

* - 43
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -10.695
  - 10.695

* - 44
  - Right Intraparietal 2
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.690
  - 10.690

* - 45
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Prefrontal Medial
  - Frontoparietal
  - Negative
  - -10.665
  - 10.665

* - 46
  - Left Intraparietal 1
  - Frontoparietal
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.657
  - 10.657

* - 47
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8C
  - Frontoparietal
  - Negative
  - -10.640
  - 10.640

* - 48
  - Left Medial Intraparietal
  - Dorsal-attention
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -10.595
  - 10.595

* - 49
  - Left Posterior Gyrus Parietal
  - Dorsal-attention
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.550
  - 10.550

* - 50
  - Right Medial Intraparietal
  - Dorsal-attention
  - Right Inferior Frontal Sulcus Posterior
  - Frontoparietal
  - Negative
  - -10.548
  - 10.548

```

## Supplementary Table S3

```{list-table} Top 50 unique functional network connections for places.
:header-rows: 1
:name: tbl-places-connections

* - Rank
  - Region 1
  - Network 1
  - Region 2
  - Network 2
  - Direction
  - t-value
  - |t|

* - 1
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - L_i6-8
  - Frontoparietal
  - Negative
  - -12.250
  - 12.250

* - 2
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -11.969
  - 11.969

* - 3
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -11.927
  - 11.927

* - 4
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -11.509
  - 11.509

* - 5
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -10.516
  - 10.516

* - 6
  - Left Intraparietal 2
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -10.422
  - 10.422

* - 7
  - L_i6-8
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -10.302
  - 10.302

* - 8
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Area 8C
  - Frontoparietal
  - Negative
  - -10.284
  - 10.284

* - 9
  - Left Area 8C
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -10.169
  - 10.169

* - 10
  - Left Intraparietal 2
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.143
  - 10.143

* - 11
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Visual Area 3
  - Visual2
  - Negative
  - -10.067
  - 10.067

* - 12
  - Left Primary Visual Cortex
  - Visual1
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.866
  - 9.866

* - 13
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -9.678
  - 9.678

* - 14
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -9.354
  - 9.354

* - 15
  - Left Retrosplenial Cortex
  - Frontoparietal
  - R_i6-8
  - Frontoparietal
  - Negative
  - -9.305
  - 9.305

* - 16
  - Left Intraparietal Sulcus 1
  - Visual2
  - Right Visual Area 3
  - Visual2
  - Negative
  - -9.198
  - 9.198

* - 17
  - Left Area 8C
  - Frontoparietal
  - Right Retrosplenial Cortex
  - Frontoparietal
  - Negative
  - -9.162
  - 9.162

* - 18
  - Left Intraparietal 1
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.975
  - 8.975

* - 19
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Area 9 Medial
  - Default
  - Positive
  - 8.946
  - 8.946

* - 20
  - Left Retrosplenial Cortex
  - Frontoparietal
  - L_i6-8
  - Frontoparietal
  - Negative
  - -8.848
  - 8.848

* - 21
  - Right Visual Area 8
  - Visual2
  - Right Ventromedial V3
  - Visual2
  - Negative
  - -8.829
  - 8.829

* - 22
  - Left Primary Visual Cortex
  - Visual1
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.816
  - 8.816

* - 23
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8BM
  - Frontoparietal
  - Negative
  - -8.781
  - 8.781

* - 24
  - Left Intraparietal 1
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -8.764
  - 8.764

* - 25
  - Left Ventromedial V3
  - Visual2
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -8.749
  - 8.749

* - 26
  - Left Somatosensory 3b
  - Somatomotor
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Positive
  - 8.710
  - 8.710

* - 27
  - Left Visual Area 3B
  - Visual2
  - Left Ventromedial V3
  - Visual2
  - Negative
  - -8.665
  - 8.665

* - 28
  - Left Intraparietal 1
  - Frontoparietal
  - Right Intraparietal 1
  - Frontoparietal
  - Negative
  - -8.623
  - 8.623

* - 29
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.542
  - 8.542

* - 30
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Secondary Visual Cortex
  - Visual2
  - Negative
  - -8.540
  - 8.540

* - 31
  - Right Retrosplenial Cortex
  - Frontoparietal
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -8.495
  - 8.495

* - 32
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.446
  - 8.446

* - 33
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8BM
  - Frontoparietal
  - Negative
  - -8.426
  - 8.426

* - 34
  - Left Visual Area 3B
  - Visual2
  - Right Visual Area 8
  - Visual2
  - Negative
  - -8.425
  - 8.425

* - 35
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8C
  - Frontoparietal
  - Negative
  - -8.414
  - 8.414

* - 36
  - Left Ventral Visual Complex
  - Visual2
  - Right Visual Area 8
  - Visual2
  - Negative
  - -8.407
  - 8.407

* - 37
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 8C
  - Frontoparietal
  - Negative
  - -8.404
  - 8.404

* - 38
  - Left Retrosplenial Cortex
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -8.391
  - 8.391

* - 39
  - Left Visual Area 3B
  - Visual2
  - Right Ventromedial V3
  - Visual2
  - Negative
  - -8.388
  - 8.388

* - 40
  - Left Visual Area 3CD
  - Visual2
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -8.299
  - 8.299

* - 41
  - Left Area 9 Medial
  - Default
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Positive
  - 8.273
  - 8.273

* - 42
  - Right Primary Visual Cortex
  - Visual1
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -8.270
  - 8.270

* - 43
  - Left Visual Area 4
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.239
  - 8.239

* - 44
  - Left Primary Visual Cortex
  - Visual1
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -8.229
  - 8.229

* - 45
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -8.203
  - 8.203

* - 46
  - Left Area p9-46v
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.195
  - 8.195

* - 47
  - Left Primary Somatosensory
  - Somatomotor
  - Right Visual Area 4 Transitional
  - Visual2
  - Negative
  - -8.164
  - 8.164

* - 48
  - Left Visual Area 4
  - Visual2
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.126
  - 8.126

* - 49
  - Left Visual Area 4
  - Visual2
  - Left Visual Area 3CD
  - Visual2
  - Negative
  - -8.121
  - 8.121

* - 50
  - Left Visual Area 3
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.118
  - 8.118

```

## Supplementary Table S4

```{list-table} Top 50 unique functional network connections for tools.
:header-rows: 1
:name: tbl-tools-connections

* - Rank
  - Region 1
  - Network 1
  - Region 2
  - Network 2
  - Direction
  - t-value
  - |t|

* - 1
  - Left Parahippocampal
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -11.875
  - 11.875

* - 2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Right Parahippocampal
  - Visual2
  - Negative
  - -10.512
  - 10.512

* - 3
  - Left Area 7 Parietal Lobule
  - Dorsal-attention
  - Left Parahippocampal
  - Visual2
  - Negative
  - -9.991
  - 9.991

* - 4
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -9.539
  - 9.539

* - 5
  - Left Visual Area 4
  - Visual2
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.513
  - 9.513

* - 6
  - Left Primary Visual Cortex
  - Visual1
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.436
  - 9.436

* - 7
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Parahippocampal
  - Visual2
  - Negative
  - -9.362
  - 9.362

* - 8
  - Left Parahippocampal
  - Visual2
  - Right Area 7 Parietal Lobule
  - Dorsal-attention
  - Negative
  - -9.311
  - 9.311

* - 9
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -9.197
  - 9.197

* - 10
  - Left Parahippocampal
  - Visual2
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.134
  - 9.134

* - 11
  - Right Visual Area 3B
  - Visual2
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -9.128
  - 9.128

* - 12
  - Left Primary Visual Cortex
  - Visual1
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -9.119
  - 9.119

* - 13
  - Left Parahippocampal
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.115
  - 9.115

* - 14
  - Left Primary Visual Cortex
  - Visual1
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.859
  - 8.859

* - 15
  - Left Area 7 Parietal Lobule
  - Dorsal-attention
  - Right Parahippocampal
  - Visual2
  - Negative
  - -8.752
  - 8.752

* - 16
  - Right Visual Area 4
  - Visual2
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.729
  - 8.729

* - 17
  - Left Visual Area 3B
  - Visual2
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.726
  - 8.726

* - 18
  - Left Primary Visual Cortex
  - Visual1
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -8.707
  - 8.707

* - 19
  - Right Primary Visual Cortex
  - Visual1
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -8.444
  - 8.444

* - 20
  - Left Parahippocampal
  - Visual2
  - Right Posterior Gyrus Parietal
  - Dorsal-attention
  - Negative
  - -8.390
  - 8.390

* - 21
  - Right Intraparietal Sulcus 1
  - Visual2
  - Right Parahippocampal
  - Visual2
  - Negative
  - -8.383
  - 8.383

* - 22
  - Left Visual Area 4
  - Visual2
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.367
  - 8.367

* - 23
  - Left Primary Visual Cortex
  - Visual1
  - Right Parietal Eye Field
  - Cingulo-Opercular
  - Negative
  - -8.347
  - 8.347

* - 24
  - Left Primary Visual Cortex
  - Visual1
  - Right Primary Visual Cortex
  - Visual1
  - Negative
  - -8.343
  - 8.343

* - 25
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -8.331
  - 8.331

* - 26
  - Right Parahippocampal
  - Visual2
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.298
  - 8.298

* - 27
  - Left Primary Visual Cortex
  - Visual1
  - Left Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.250
  - 8.250

* - 28
  - Left Intraparietal Sulcus 1
  - Visual2
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -8.240
  - 8.240

* - 29
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Left Parahippocampal
  - Visual2
  - Negative
  - -8.202
  - 8.202

* - 30
  - Left Parahippocampal
  - Visual2
  - Right Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -8.184
  - 8.184

* - 31
  - Left Visual Area 4
  - Visual2
  - Left Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -8.157
  - 8.157

* - 32
  - Left Area 7 Parietal Lobule
  - Dorsal-attention
  - Right Lateral Occipital 3
  - Visual2
  - Negative
  - -8.157
  - 8.157

* - 33
  - Left Visual Area 4
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.155
  - 8.155

* - 34
  - Left Intraparietal Sulcus 1
  - Visual2
  - Left Visual Area 3B
  - Visual2
  - Negative
  - -8.141
  - 8.141

* - 35
  - Left Parahippocampal
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.120
  - 8.120

* - 36
  - Left Visual Area 4
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.112
  - 8.112

* - 37
  - Right Area 7 Parietal Lobule
  - Dorsal-attention
  - Right Parahippocampal
  - Visual2
  - Negative
  - -8.087
  - 8.087

* - 38
  - Left Parahippocampal
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -8.085
  - 8.085

* - 39
  - Left Area 7 Parietal Lobule
  - Dorsal-attention
  - Right Lateral Intraparietal Ventral
  - Visual2
  - Negative
  - -8.067
  - 8.067

* - 40
  - Right Visual Area 3B
  - Visual2
  - Right Parahippocampal
  - Visual2
  - Negative
  - -8.062
  - 8.062

* - 41
  - Right Lateral Occipital 1
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -8.055
  - 8.055

* - 42
  - Left Visual Area 3B
  - Visual2
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.020
  - 8.020

* - 43
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -7.988
  - 7.988

* - 44
  - Left Visual Area 7
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -7.972
  - 7.972

* - 45
  - Left Visual Area 3
  - Visual2
  - Left Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -7.967
  - 7.967

* - 46
  - Left Visual Area 4
  - Visual2
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -7.965
  - 7.965

* - 47
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Right Visual Area 3A
  - Visual2
  - Negative
  - -7.950
  - 7.950

* - 48
  - Left Visual Area 7
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -7.917
  - 7.917

* - 49
  - Right Visual Area 3B
  - Visual2
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -7.905
  - 7.905

* - 50
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Right Visual Area 3A
  - Visual2
  - Negative
  - -7.882
  - 7.882

```

## Supplementary Table S5

```{list-table} Top 50 shared functional network connections.
:header-rows: 1
:name: tbl-shared-connections

* - Rank
  - Region 1
  - Network 1
  - Region 2
  - Network 2
  - Direction
  - Common t-value
  - |Common t|
  - t (Face)
  - t (Body)
  - t (Places)
  - t (Tools)

* - 1
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -11.211
  - 11.211
  - -14.721
  - -12.232
  - -11.922
  - -5.971

* - 2
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area p9-46v
  - Frontoparietal
  - Negative
  - -11.194
  - 11.194
  - -12.785
  - -14.269
  - -11.837
  - -5.886

* - 3
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -10.937
  - 10.937
  - -10.715
  - -12.764
  - -9.843
  - -10.425

* - 4
  - Right Medial Intraparietal
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.931
  - 10.931
  - -12.863
  - -13.285
  - -8.510
  - -9.065

* - 5
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Area p9-46v
  - Frontoparietal
  - Negative
  - -10.726
  - 10.726
  - -12.797
  - -12.582
  - -11.324
  - -6.202

* - 6
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.565
  - 10.565
  - -14.014
  - -13.061
  - -7.991
  - -7.194

* - 7
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 7 Posterior Medial
  - Frontoparietal
  - Negative
  - -10.524
  - 10.524
  - -11.755
  - -13.351
  - -11.583
  - -5.405

* - 8
  - Left Medial Intraparietal
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.437
  - 10.437
  - -10.645
  - -12.860
  - -10.208
  - -8.035

* - 9
  - Left Area p9-46v
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -10.401
  - 10.401
  - -11.493
  - -11.627
  - -11.764
  - -6.719

* - 10
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.400
  - 10.400
  - -9.673
  - -13.521
  - -9.459
  - -8.947

* - 11
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -10.225
  - 10.225
  - -10.738
  - -14.082
  - -8.342
  - -7.740

* - 12
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -10.135
  - 10.135
  - -11.278
  - -14.414
  - -6.486
  - -8.361

* - 13
  - Left Visual Area 3B
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -9.994
  - 9.994
  - -9.370
  - -12.672
  - -7.860
  - -10.074

* - 14
  - Left Medial Intraparietal
  - Dorsal-attention
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -9.877
  - 9.877
  - -10.666
  - -11.581
  - -9.439
  - -7.822

* - 15
  - Right Visual Area 3B
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -9.859
  - 9.859
  - -10.445
  - -11.568
  - -6.455
  - -10.970

* - 16
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area 7 Posterior Medial
  - Frontoparietal
  - Negative
  - -9.844
  - 9.844
  - -9.363
  - -12.643
  - -11.731
  - -5.638

* - 17
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Negative
  - -9.842
  - 9.842
  - -9.417
  - -11.389
  - -11.387
  - -7.174

* - 18
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.657
  - 9.657
  - -11.070
  - -13.096
  - -6.393
  - -8.066

* - 19
  - Left Medial Intraparietal
  - Dorsal-attention
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.608
  - 9.608
  - -10.237
  - -11.722
  - -8.286
  - -8.186

* - 20
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.537
  - 9.537
  - -11.308
  - -11.939
  - -8.546
  - -6.356

* - 21
  - Left Area 7 Posterior Medial
  - Frontoparietal
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Negative
  - -9.434
  - 9.434
  - -8.424
  - -11.104
  - -10.716
  - -7.492

* - 22
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.427
  - 9.427
  - -11.639
  - -11.990
  - -7.874
  - -6.205

* - 23
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Intraparietal 2
  - Frontoparietal
  - Negative
  - -9.299
  - 9.299
  - -10.767
  - -9.544
  - -10.814
  - -6.069

* - 24
  - Right Medial Intraparietal
  - Dorsal-attention
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -9.278
  - 9.278
  - -10.232
  - -12.424
  - -7.193
  - -7.264

* - 25
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Right Intraparietal 0
  - Dorsal-attention
  - Negative
  - -9.267
  - 9.267
  - -9.631
  - -10.760
  - -9.989
  - -6.688

* - 26
  - Left Visual Area 3CD
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -9.196
  - 9.196
  - -11.120
  - -11.497
  - -7.015
  - -7.150

* - 27
  - Left Visual Area 3B
  - Visual2
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -9.012
  - 9.012
  - -11.133
  - -8.772
  - -7.356
  - -8.785

* - 28
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.969
  - 8.969
  - -8.936
  - -10.605
  - -7.398
  - -8.936

* - 29
  - Left Intraparietal Sulcus 1
  - Visual2
  - Right Medial Intraparietal
  - Dorsal-attention
  - Negative
  - -8.947
  - 8.947
  - -10.368
  - -10.354
  - -6.184
  - -8.881

* - 30
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.934
  - 8.934
  - -9.184
  - -11.490
  - -7.587
  - -7.476

* - 31
  - Right Visual Area 3B
  - Visual2
  - Right Anterior Intraparietal
  - Dorsal-attention
  - Negative
  - -8.932
  - 8.932
  - -10.485
  - -10.800
  - -6.254
  - -8.191

* - 32
  - Left Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Left Area a9-46v
  - Frontoparietal
  - Negative
  - -8.844
  - 8.844
  - -9.714
  - -9.106
  - -9.138
  - -7.416

* - 33
  - Left Area p9-46v
  - Frontoparietal
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.785
  - 8.785
  - -10.060
  - -9.643
  - -8.460
  - -6.975

* - 34
  - Left Medial Intraparietal
  - Dorsal-attention
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.744
  - 8.744
  - -9.403
  - -11.605
  - -7.819
  - -6.150

* - 35
  - Left Intraparietal 2
  - Frontoparietal
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.731
  - 8.731
  - -9.453
  - -11.075
  - -7.575
  - -6.819

* - 36
  - Left Area p9-46v
  - Frontoparietal
  - Right Dorsal Visual Temporal
  - Visual1
  - Negative
  - -8.599
  - 8.599
  - -9.544
  - -11.517
  - -6.415
  - -6.920

* - 37
  - Left Anterior Intraparietal
  - Dorsal-attention
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.548
  - 8.548
  - -10.687
  - -8.741
  - -7.011
  - -7.754

* - 38
  - Left Intraparietal Sulcus 1
  - Visual2
  - Left Intraparietal 0
  - Dorsal-attention
  - Negative
  - -8.548
  - 8.548
  - -9.687
  - -9.206
  - -6.679
  - -8.622

* - 39
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Right Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Negative
  - -8.546
  - 8.546
  - -8.369
  - -11.942
  - -6.109
  - -7.764

* - 40
  - Right Visual Area 3B
  - Visual2
  - Right Intraparietal 2
  - Frontoparietal
  - Negative
  - -8.544
  - 8.544
  - -8.898
  - -13.626
  - -5.750
  - -5.902

* - 41
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.536
  - 8.536
  - -8.677
  - -9.771
  - -6.261
  - -9.435

* - 42
  - Left Intraparietal 0
  - Dorsal-attention
  - Right Visual Area 3B
  - Visual2
  - Negative
  - -8.529
  - 8.529
  - -6.675
  - -8.170
  - -8.593
  - -10.679

* - 43
  - Left Intraparietal Sulcus 1
  - Visual2
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Negative
  - -8.503
  - 8.503
  - -8.713
  - -11.691
  - -6.149
  - -7.458

* - 44
  - Left Visual Area 3CD
  - Visual2
  - Right Intraparietal Sulcus 1
  - Visual2
  - Negative
  - -8.459
  - 8.459
  - -7.186
  - -10.186
  - -6.784
  - -9.679

* - 45
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Visual Area 3CD
  - Visual2
  - Negative
  - -8.457
  - 8.457
  - -9.972
  - -11.654
  - -6.295
  - -5.906

* - 46
  - Left Lateral Intraparietal Dorsal
  - Dorsal-attention
  - Right Primary Visual Cortex
  - Visual1
  - Negative
  - -8.455
  - 8.455
  - -11.129
  - -7.245
  - -9.394
  - -6.051

* - 47
  - Left Medial Intraparietal
  - Dorsal-attention
  - Left Parahippocampal
  - Visual2
  - Negative
  - -8.440
  - 8.440
  - -9.473
  - -8.080
  - -6.234
  - -9.972

* - 48
  - Right Parieto-Occipital Sulcus 2
  - Frontoparietal
  - Right Area a9-46v
  - Frontoparietal
  - Negative
  - -8.434
  - 8.434
  - -7.436
  - -8.405
  - -7.583
  - -10.310

* - 49
  - Left Visual Area 3B
  - Visual2
  - Left Area p9-46v
  - Frontoparietal
  - Negative
  - -8.431
  - 8.431
  - -10.638
  - -8.589
  - -7.985
  - -6.512

* - 50
  - Left Inferior Frontal Junction Posterior
  - Frontoparietal
  - Left Visual Area 3CD
  - Visual2
  - Negative
  - -8.423
  - 8.423
  - -10.276
  - -9.449
  - -7.485
  - -6.483

```

## Supplementary Table S6

```{list-table} Node labels and network assignments.
:header-rows: 1
:name: tbl-node-labels

* - short_label
  - full_label
  - original_label
  - network
  - hemisphere

* - L-thalamus
  - Left Thalamus
  - thalamus_left
  - Subcortical
  - L

* - L-putamen
  - Left Putamen
  - putamen_left
  - Subcortical
  - L

* - L-pallidum
  - Left Pallidum
  - pallidum_left
  - Subcortical
  - L

* - L-hippocampus
  - Left Hippocampus
  - hippocampus_left
  - Subcortical
  - L

* - L-diencephalon
  - diencephalon_left
  - diencephalon_left
  - Subcortical
  - L

* - L-cerebellum
  - Left Cerebellum
  - cerebellum_left
  - Subcortical
  - L

* - L-caudate
  - Left Caudate
  - caudate_left
  - Subcortical
  - L

* - L-amygdala
  - Left Amygdala
  - amygdala_left
  - Subcortical
  - L

* - L-accumbens
  - Left Accumbens
  - accumbens_left
  - Subcortical
  - L

* - L_pOFC
  - Left Posterior Orbitofrontal Cortex
  - L_pOFC
  - Orbito-Affective
  - L

* - L_Pir
  - Left Piriform
  - L_Pir
  - Orbito-Affective
  - L

* - L_AAIC
  - Left Anterior Agranular Insula
  - L_AAIC
  - Orbito-Affective
  - L

* - L_TPOJ3
  - Left Temporo-Parietal Junction 3
  - L_TPOJ3
  - Posterior-Multimodal
  - L

* - L_TPOJ2
  - Left Temporo-Parietal Junction 2
  - L_TPOJ2
  - Posterior-Multimodal
  - L

* - L_PCV
  - Left Posterior Cingulate Ventral
  - L_PCV
  - Posterior-Multimodal
  - L

* - L_v23ab
  - Left Area 23 Ventral
  - L_v23ab
  - Default
  - L

* - L_s32
  - Left Superior Area 32
  - L_s32
  - Default
  - L

* - L_p32
  - Left Posterior Area 32
  - L_p32
  - Default
  - L

* - L_d32
  - Left Dorsal Area 32
  - L_d32
  - Default
  - L

* - L_d23ab
  - Left Area 23 Dorsal
  - L_d23ab
  - Default
  - L

* - L_a24
  - Left Anterior Cingulate 24
  - L_a24
  - Default
  - L

* - L_TGd
  - Left Temporal Gyrus Dorsal
  - L_TGd
  - Default
  - L

* - L_TE2a
  - Left Temporal Area 2a
  - L_TE2a
  - Default
  - L

* - L_TE1m
  - Left Temporal Area 1m
  - L_TE1m
  - Default
  - L

* - L_TE1a
  - Left Temporal Area 1a
  - L_TE1a
  - Default
  - L

* - L_STSvp
  - Left Superior Temporal Sulcus Ventral Posterior
  - L_STSvp
  - Default
  - L

* - L_STSva
  - Left Superior Temporal Sulcus Ventral Anterior
  - L_STSva
  - Default
  - L

* - L_PreS
  - Left Presubiculum
  - L_PreS
  - Default
  - L

* - L_POS1
  - Left Parieto-Occipital Sulcus 1
  - L_POS1
  - Default
  - L

* - L_PHA2
  - Left Parahippocampal 2
  - L_PHA2
  - Default
  - L

* - L_PHA1
  - Left Parahippocampal 1
  - L_PHA1
  - Default
  - L

* - L_PGs
  - Left Posterior Gyrus Superior
  - L_PGs
  - Default
  - L

* - L_PGi
  - Left Posterior Gyrus Inferior
  - L_PGi
  - Default
  - L

* - L_OFC
  - Left Orbitofrontal Cortex
  - L_OFC
  - Default
  - L

* - L_H
  - Left Hippocampus
  - L_H
  - Default
  - L

* - L_EC
  - Left Entorhinal Cortex
  - L_EC
  - Default
  - L

* - L_9p
  - Left Area 9 Posterior
  - L_9p
  - Default
  - L

* - L_9m
  - Left Area 9 Medial
  - L_9m
  - Default
  - L

* - L_9a
  - Left Area 9a
  - L_9a
  - Default
  - L

* - L_8BL
  - Left Area 8B Lateral
  - L_8BL
  - Default
  - L

* - L_8Av
  - Left Area 8A Ventral
  - L_8Av
  - Default
  - L

* - L_8Ad
  - Left Area 8A Dorsal
  - L_8Ad
  - Default
  - L

* - L_7m
  - Left Area 7 Medial
  - L_7m
  - Default
  - L

* - L_47s
  - Left Area 47 Superior
  - L_47s
  - Default
  - L

* - L_47m
  - L_47m
  - L_47m
  - Default
  - L

* - L_47l
  - Left Area 47 Lateral
  - L_47l
  - Default
  - L

* - L_31pv
  - Left Area 31 Posterior Ventral
  - L_31pv
  - Default
  - L

* - L_31pd
  - Left Area 31 Posterior Dorsal
  - L_31pd
  - Default
  - L

* - L_31a
  - Left Area 31 Anterior
  - L_31a
  - Default
  - L

* - L_25
  - Left Area 25 (Subgenual)
  - L_25
  - Default
  - L

* - L_23d
  - Left Area 23 Dorsal
  - L_23d
  - Default
  - L

* - L_10v
  - Left Area 10 Ventral
  - L_10v
  - Default
  - L

* - L_10r
  - Left Area 10 Rostral
  - L_10r
  - Default
  - L

* - L_10pp
  - Left Area 10 Posterior Pole
  - L_10pp
  - Default
  - L

* - L_10d
  - Left Area 10 Dorsal
  - L_10d
  - Default
  - L

* - L_s6-8
  - L_s6-8
  - L_s6-8
  - Frontoparietal
  - L

* - L_p9-46v
  - L_p9-46v
  - L_p9-46v
  - Frontoparietal
  - L

* - L_p47r
  - Left Area p47r
  - L_p47r
  - Frontoparietal
  - L

* - L_p10p
  - Left Area p10p
  - L_p10p
  - Frontoparietal
  - L

* - L_i6-8
  - L_i6-8
  - L_i6-8
  - Frontoparietal
  - L

* - L_a9-46v
  - L_a9-46v
  - L_a9-46v
  - Frontoparietal
  - L

* - L_a47r
  - Left Area 47 Right
  - L_a47r
  - Frontoparietal
  - L

* - L_a10p
  - Left Area a10p
  - L_a10p
  - Frontoparietal
  - L

* - L_TE1p
  - Left Temporal Area 1p
  - L_TE1p
  - Frontoparietal
  - L

* - L_RSC
  - L_RSC
  - L_RSC
  - Frontoparietal
  - L

* - L_POS2
  - Left Parieto-Occipital Sulcus 2
  - L_POS2
  - Frontoparietal
  - L

* - L_PFm
  - Left Prefrontal Medial
  - L_PFm
  - Frontoparietal
  - L

* - L_IP2
  - Left Intraparietal 2
  - L_IP2
  - Frontoparietal
  - L

* - L_IP1
  - Left Intraparietal 1
  - L_IP1
  - Frontoparietal
  - L

* - L_IFSa
  - Left Inferior Frontal Sulcus Anterior
  - L_IFSa
  - Frontoparietal
  - L

* - L_IFJp
  - Left Inferior Frontal Junction Posterior
  - L_IFJp
  - Frontoparietal
  - L

* - L_AVI
  - Left Anterior Ventral Insula
  - L_AVI
  - Frontoparietal
  - L

* - L_8C
  - Left Area 8C
  - L_8C
  - Frontoparietal
  - L

* - L_8BM
  - Left Area 8BM
  - L_8BM
  - Frontoparietal
  - L

* - L_7Pm
  - Left Area 7 Posterior Medial
  - L_7Pm
  - Frontoparietal
  - L

* - L_13l
  - Left Area 13 Lateral (Insula)
  - L_13l
  - Frontoparietal
  - L

* - L_11l
  - Left Area 11 Lateral
  - L_11l
  - Frontoparietal
  - L

* - L_TPOJ1
  - Left Temporo-Parietal Junction 1
  - L_TPOJ1
  - Language
  - L

* - L_TGv
  - Left Temporal Gyrus Ventral
  - L_TGv
  - Language
  - L

* - L_STV
  - Left Superior Temporal Ventral
  - L_STV
  - Language
  - L

* - L_STSdp
  - Left Superior Temporal Sulcus Dorsal Posterior
  - L_STSdp
  - Language
  - L

* - L_STSda
  - Left Superior Temporal Sulcus Dorsal Anterior
  - L_STSda
  - Language
  - L

* - L_STGa
  - Left Superior Temporal Gyrus Anterior
  - L_STGa
  - Language
  - L

* - L_SFL
  - Left Superior Frontal Lobule
  - L_SFL
  - Language
  - L

* - L_PSL
  - Left Parietal Superior Lobule
  - L_PSL
  - Language
  - L

* - L_IFSp
  - Left Inferior Frontal Sulcus Posterior
  - L_IFSp
  - Language
  - L

* - L_IFJa
  - Left Inferior Frontal Junction Anterior
  - L_IFJa
  - Language
  - L

* - L_A5
  - Left Auditory Area 5
  - L_A5
  - Language
  - L

* - L_55b
  - Left Area 55b
  - L_55b
  - Language
  - L

* - L_45
  - Left Area 45 (Broca)
  - L_45
  - Language
  - L

* - L_44
  - Left Area 44 (Broca)
  - L_44
  - Language
  - L

* - L_p32pr
  - Left Posterior Area 32pr
  - L_p32pr
  - Cingulo-Opercular
  - L

* - L_p24pr
  - Left Posterior Cingulate 24pr
  - L_p24pr
  - Cingulo-Opercular
  - L

* - L_p24
  - Left Posterior Cingulate 24
  - L_p24
  - Cingulo-Opercular
  - L

* - L_a32pr
  - L_a32pr
  - L_a32pr
  - Cingulo-Opercular
  - L

* - L_a24pr
  - Left Anterior Cingulate 24pr
  - L_a24pr
  - Cingulo-Opercular
  - L

* - L_SCEF
  - Left Supplementary Cingulate Eye Field
  - L_SCEF
  - Cingulo-Opercular
  - L

* - L_PoI2
  - Left Postcentral Insula 2
  - L_PoI2
  - Cingulo-Opercular
  - L

* - L_PoI1
  - Left Postcentral Insula 1
  - L_PoI1
  - Cingulo-Opercular
  - L

* - L_PI
  - Left Posterior Insula
  - L_PI
  - Cingulo-Opercular
  - L

* - L_PFop
  - Left Prefrontal Opercular
  - L_PFop
  - Cingulo-Opercular
  - L

* - L_PFcm
  - Left Prefrontal Cortex Medial
  - L_PFcm
  - Cingulo-Opercular
  - L

* - L_PF
  - Left Prefrontal
  - L_PF
  - Cingulo-Opercular
  - L

* - L_MI
  - Left Motor Insula
  - L_MI
  - Cingulo-Opercular
  - L

* - L_FOP5
  - Left Frontal Opercular 5
  - L_FOP5
  - Cingulo-Opercular
  - L

* - L_FOP4
  - Left Frontal Opercular 4
  - L_FOP4
  - Cingulo-Opercular
  - L

* - L_FOP3
  - Left Frontal Opercular 3
  - L_FOP3
  - Cingulo-Opercular
  - L

* - L_FOP1
  - Left Frontal Opercular 1
  - L_FOP1
  - Cingulo-Opercular
  - L

* - L_FEF
  - Left Frontal Eye Field
  - L_FEF
  - Cingulo-Opercular
  - L

* - L_9-46d
  - L_9-46d
  - L_9-46d
  - Cingulo-Opercular
  - L

* - L_7Am
  - Left Area 7 Medial
  - L_7Am
  - Cingulo-Opercular
  - L

* - L_6r
  - Left Premotor 6r
  - L_6r
  - Cingulo-Opercular
  - L

* - L_6ma
  - Left Area 6ma
  - L_6ma
  - Cingulo-Opercular
  - L

* - L_5mv
  - Left Area 5 Medial Ventral
  - L_5mv
  - Cingulo-Opercular
  - L

* - L_46
  - Left Area 46 (Dorsolateral Prefrontal)
  - L_46
  - Cingulo-Opercular
  - L

* - L_43
  - Left Area 43
  - L_43
  - Cingulo-Opercular
  - L

* - L_33pr
  - Left Area 33pr
  - L_33pr
  - Cingulo-Opercular
  - L

* - L_23c
  - Left Area 23c
  - L_23c
  - Cingulo-Opercular
  - L

* - L_TF
  - Left Temporal Fusiform
  - L_TF
  - Ventral-Multimodal
  - L

* - L_PeEc
  - Left Perirhinal Entorhinal Cortex
  - L_PeEc
  - Ventral-Multimodal
  - L

* - L_TE2p
  - Left Temporal Area 2p
  - L_TE2p
  - Dorsal-attention
  - L

* - L_PHT
  - Left Parahippocampal Temporal
  - L_PHT
  - Dorsal-attention
  - L

* - L_PHA3
  - Left Parahippocampal 3
  - L_PHA3
  - Dorsal-attention
  - L

* - L_PGp
  - Left Posterior Gyrus Parietal
  - L_PGp
  - Dorsal-attention
  - L

* - L_PFt
  - Left Prefrontal Temporal
  - L_PFt
  - Dorsal-attention
  - L

* - L_PEF
  - Left Parietal Eye Field
  - L_PEF
  - Dorsal-attention
  - L

* - L_MIP
  - Left Medial Intraparietal
  - L_MIP
  - Dorsal-attention
  - L

* - L_LIPd
  - Left Lateral Intraparietal Dorsal
  - L_LIPd
  - Dorsal-attention
  - L

* - L_IP0
  - Left Intraparietal 0
  - L_IP0
  - Dorsal-attention
  - L

* - L_AIP
  - Left Anterior Intraparietal
  - L_AIP
  - Dorsal-attention
  - L

* - L_7PL
  - Left Area 7 Parietal Lobule
  - L_7PL
  - Dorsal-attention
  - L

* - L_6a
  - Left Premotor 6a
  - L_6a
  - Dorsal-attention
  - L

* - L_TA2
  - Left Temporal Area 2
  - L_TA2
  - Auditory
  - L

* - L_RI
  - L_RI
  - L_RI
  - Auditory
  - L

* - L_PBelt
  - Left Posterior Belt
  - L_PBelt
  - Auditory
  - L

* - L_MBelt
  - Left Medial Belt
  - L_MBelt
  - Auditory
  - L

* - L_LBelt
  - Left Lateral Belt
  - L_LBelt
  - Auditory
  - L

* - L_A4
  - Left Auditory Area 4
  - L_A4
  - Auditory
  - L

* - L_A1
  - Left Primary Auditory Cortex
  - L_A1
  - Auditory
  - L

* - L_52
  - Left Area 52
  - L_52
  - Auditory
  - L

* - L_OP4
  - Left Opercular 4
  - L_OP4
  - Somatomotor
  - L

* - L_OP2-3
  - L_OP2-3
  - L_OP2-3
  - Somatomotor
  - L

* - L_OP1
  - Left Opercular 1
  - L_OP1
  - Somatomotor
  - L

* - L_Ig
  - Left Granular Insula
  - L_Ig
  - Somatomotor
  - L

* - L_FOP2
  - Left Frontal Opercular 2
  - L_FOP2
  - Somatomotor
  - L

* - L_7PC
  - Left Area 7 Parietal Convexity
  - L_7PC
  - Somatomotor
  - L

* - L_7AL
  - Left Area 7 Anterior Lobule
  - L_7AL
  - Somatomotor
  - L

* - L_6v
  - Left Premotor 6v
  - L_6v
  - Somatomotor
  - L

* - L_6mp
  - Left Premotor 6mp
  - L_6mp
  - Somatomotor
  - L

* - L_6d
  - Left Premotor 6d
  - L_6d
  - Somatomotor
  - L

* - L_5m
  - Left Area 5 Medial
  - L_5m
  - Somatomotor
  - L

* - L_5L
  - Left Area 5 Lateral
  - L_5L
  - Somatomotor
  - L

* - L_4
  - Left Primary Motor Cortex
  - L_4
  - Somatomotor
  - L

* - L_3b
  - Left Somatosensory 3b
  - L_3b
  - Somatomotor
  - L

* - L_3a
  - Left Somatosensory 3a
  - L_3a
  - Somatomotor
  - L

* - L_24dv
  - Left Anterior Cingulate 24dv
  - L_24dv
  - Somatomotor
  - L

* - L_24dd
  - Left Anterior Cingulate 24dd
  - L_24dd
  - Somatomotor
  - L

* - L_2
  - Left Secondary Somatosensory
  - L_2
  - Somatomotor
  - L

* - L_1
  - Left Primary Somatosensory
  - L_1
  - Somatomotor
  - L

* - L_VVC
  - Left Ventral Visual Complex
  - L_VVC
  - Visual2
  - L

* - L_VMV3
  - Left Ventromedial V3
  - L_VMV3
  - Visual2
  - L

* - L_VMV2
  - Left Ventromedial V2
  - L_VMV2
  - Visual2
  - L

* - L_VMV1
  - Left Ventromedial V1
  - L_VMV1
  - Visual2
  - L

* - L_VIP
  - Left Ventral Intraparietal
  - L_VIP
  - Visual2
  - L

* - L_V8
  - Left Visual Area 8
  - L_V8
  - Visual2
  - L

* - L_V7
  - Left Visual Area 7
  - L_V7
  - Visual2
  - L

* - L_V6A
  - Left Visual Area 6A
  - L_V6A
  - Visual2
  - L

* - L_V6
  - Left Visual Area 6
  - L_V6
  - Visual2
  - L

* - L_V4t
  - Left Visual Area 4 Transitional
  - L_V4t
  - Visual2
  - L

* - L_V4
  - Left Visual Area 4
  - L_V4
  - Visual2
  - L

* - L_V3CD
  - Left Visual Area 3CD
  - L_V3CD
  - Visual2
  - L

* - L_V3B
  - Left Visual Area 3B
  - L_V3B
  - Visual2
  - L

* - L_V3A
  - Left Visual Area 3A
  - L_V3A
  - Visual2
  - L

* - L_V3
  - Left Visual Area 3
  - L_V3
  - Visual2
  - L

* - L_V2
  - Left Secondary Visual Cortex
  - L_V2
  - Visual2
  - L

* - L_PIT
  - Left Posterior Inferotemporal
  - L_PIT
  - Visual2
  - L

* - L_PH
  - Left Parahippocampal
  - L_PH
  - Visual2
  - L

* - L_MT
  - Left Middle Temporal
  - L_MT
  - Visual2
  - L

* - L_MST
  - Left Medial Superior Temporal
  - L_MST
  - Visual2
  - L

* - L_LO3
  - Left Lateral Occipital 3
  - L_LO3
  - Visual2
  - L

* - L_LO2
  - Left Lateral Occipital 2
  - L_LO2
  - Visual2
  - L

* - L_LO1
  - Left Lateral Occipital 1
  - L_LO1
  - Visual2
  - L

* - L_LIPv
  - Left Lateral Intraparietal Ventral
  - L_LIPv
  - Visual2
  - L

* - L_IPS1
  - Left Intraparietal Sulcus 1
  - L_IPS1
  - Visual2
  - L

* - L_FST
  - Left Fundus of Superior Temporal
  - L_FST
  - Visual2
  - L

* - L_FFC
  - Left Fusiform Face Complex
  - L_FFC
  - Visual2
  - L

* - L_V1
  - Left Primary Visual Cortex
  - L_V1
  - Visual1
  - L

* - L_ProS
  - Left Prosubiculum
  - L_ProS
  - Visual1
  - L

* - L_DVT
  - Left Dorsal Visual Temporal
  - L_DVT
  - Visual1
  - L

* - R_DVT
  - Right Dorsal Visual Temporal
  - R_DVT
  - Visual1
  - R

* - R_ProS
  - Right Prosubiculum
  - R_ProS
  - Visual1
  - R

* - R_V1
  - Right Primary Visual Cortex
  - R_V1
  - Visual1
  - R

* - R_FFC
  - Right Fusiform Face Complex
  - R_FFC
  - Visual2
  - R

* - R_FST
  - Right Fundus of Superior Temporal
  - R_FST
  - Visual2
  - R

* - R_IPS1
  - Right Intraparietal Sulcus 1
  - R_IPS1
  - Visual2
  - R

* - R_LIPv
  - Right Lateral Intraparietal Ventral
  - R_LIPv
  - Visual2
  - R

* - R_LO1
  - Right Lateral Occipital 1
  - R_LO1
  - Visual2
  - R

* - R_LO2
  - Right Lateral Occipital 2
  - R_LO2
  - Visual2
  - R

* - R_LO3
  - Right Lateral Occipital 3
  - R_LO3
  - Visual2
  - R

* - R_MST
  - Right Medial Superior Temporal
  - R_MST
  - Visual2
  - R

* - R_MT
  - Right Middle Temporal
  - R_MT
  - Visual2
  - R

* - R_PH
  - Right Parahippocampal
  - R_PH
  - Visual2
  - R

* - R_PIT
  - Right Posterior Inferotemporal
  - R_PIT
  - Visual2
  - R

* - R_V2
  - Right Secondary Visual Cortex
  - R_V2
  - Visual2
  - R

* - R_V3
  - Right Visual Area 3
  - R_V3
  - Visual2
  - R

* - R_V3A
  - Right Visual Area 3A
  - R_V3A
  - Visual2
  - R

* - R_V3B
  - Right Visual Area 3B
  - R_V3B
  - Visual2
  - R

* - R_V3CD
  - Right Visual Area 3CD
  - R_V3CD
  - Visual2
  - R

* - R_V4
  - Right Visual Area 4
  - R_V4
  - Visual2
  - R

* - R_V4t
  - Right Visual Area 4 Transitional
  - R_V4t
  - Visual2
  - R

* - R_V6
  - Right Visual Area 6
  - R_V6
  - Visual2
  - R

* - R_V6A
  - Right Visual Area 6A
  - R_V6A
  - Visual2
  - R

* - R_V7
  - Right Visual Area 7
  - R_V7
  - Visual2
  - R

* - R_V8
  - Right Visual Area 8
  - R_V8
  - Visual2
  - R

* - R_VIP
  - Right Ventral Intraparietal
  - R_VIP
  - Visual2
  - R

* - R_VMV1
  - Right Ventromedial V1
  - R_VMV1
  - Visual2
  - R

* - R_VMV2
  - Right Ventromedial V2
  - R_VMV2
  - Visual2
  - R

* - R_VMV3
  - Right Ventromedial V3
  - R_VMV3
  - Visual2
  - R

* - R_VVC
  - Right Ventral Visual Complex
  - R_VVC
  - Visual2
  - R

* - R_1
  - Right Primary Somatosensory
  - R_1
  - Somatomotor
  - R

* - R_2
  - Right Secondary Somatosensory
  - R_2
  - Somatomotor
  - R

* - R_24dd
  - Right Anterior Cingulate 24dd
  - R_24dd
  - Somatomotor
  - R

* - R_24dv
  - Right Anterior Cingulate 24dv
  - R_24dv
  - Somatomotor
  - R

* - R_3a
  - Right Somatosensory 3a
  - R_3a
  - Somatomotor
  - R

* - R_3b
  - Right Somatosensory 3b
  - R_3b
  - Somatomotor
  - R

* - R_4
  - Right Primary Motor Cortex
  - R_4
  - Somatomotor
  - R

* - R_5L
  - Right Area 5 Lateral
  - R_5L
  - Somatomotor
  - R

* - R_5m
  - Right Area 5 Medial
  - R_5m
  - Somatomotor
  - R

* - R_6d
  - Right Premotor 6d
  - R_6d
  - Somatomotor
  - R

* - R_6mp
  - Right Premotor 6mp
  - R_6mp
  - Somatomotor
  - R

* - R_6v
  - Right Premotor 6v
  - R_6v
  - Somatomotor
  - R

* - R_7AL
  - Right Area 7 Anterior Lobule
  - R_7AL
  - Somatomotor
  - R

* - R_7PC
  - Right Area 7 Parietal Convexity
  - R_7PC
  - Somatomotor
  - R

* - R_FOP2
  - Right Frontal Opercular 2
  - R_FOP2
  - Somatomotor
  - R

* - R_Ig
  - Right Granular Insula
  - R_Ig
  - Somatomotor
  - R

* - R_OP1
  - Right Opercular 1
  - R_OP1
  - Somatomotor
  - R

* - R_OP2-3
  - R_OP2-3
  - R_OP2-3
  - Somatomotor
  - R

* - R_OP4
  - Right Opercular 4
  - R_OP4
  - Somatomotor
  - R

* - R_RI
  - Right Retroinsular
  - R_RI
  - Somatomotor
  - R

* - R_52
  - Right Area 52
  - R_52
  - Auditory
  - R

* - R_A1
  - Right Primary Auditory Cortex
  - R_A1
  - Auditory
  - R

* - R_A4
  - Right Auditory Area 4
  - R_A4
  - Auditory
  - R

* - R_LBelt
  - Right Lateral Belt
  - R_LBelt
  - Auditory
  - R

* - R_MBelt
  - Right Medial Belt
  - R_MBelt
  - Auditory
  - R

* - R_PBelt
  - Right Posterior Belt
  - R_PBelt
  - Auditory
  - R

* - R_TA2
  - Right Temporal Area 2
  - R_TA2
  - Auditory
  - R

* - R_6a
  - Right Premotor 6a
  - R_6a
  - Dorsal-attention
  - R

* - R_7PL
  - Right Area 7 Parietal Lobule
  - R_7PL
  - Dorsal-attention
  - R

* - R_AIP
  - Right Anterior Intraparietal
  - R_AIP
  - Dorsal-attention
  - R

* - R_IP0
  - Right Intraparietal 0
  - R_IP0
  - Dorsal-attention
  - R

* - R_LIPd
  - Right Lateral Intraparietal Dorsal
  - R_LIPd
  - Dorsal-attention
  - R

* - R_MIP
  - Right Medial Intraparietal
  - R_MIP
  - Dorsal-attention
  - R

* - R_PFt
  - Right Prefrontal Temporal
  - R_PFt
  - Dorsal-attention
  - R

* - R_PGp
  - Right Posterior Gyrus Parietal
  - R_PGp
  - Dorsal-attention
  - R

* - R_PHA3
  - Right Parahippocampal 3
  - R_PHA3
  - Dorsal-attention
  - R

* - R_PHT
  - Right Parahippocampal Temporal
  - R_PHT
  - Dorsal-attention
  - R

* - R_TE2p
  - Right Temporal Area 2p
  - R_TE2p
  - Dorsal-attention
  - R

* - R_PeEc
  - Right Perirhinal Entorhinal Cortex
  - R_PeEc
  - Ventral-Multimodal
  - R

* - R_TF
  - Right Temporal Fusiform
  - R_TF
  - Ventral-Multimodal
  - R

* - R_23c
  - Right Area 23c
  - R_23c
  - Cingulo-Opercular
  - R

* - R_43
  - Right Area 43
  - R_43
  - Cingulo-Opercular
  - R

* - R_46
  - Right Area 46 (Dorsolateral Prefrontal)
  - R_46
  - Cingulo-Opercular
  - R

* - R_5mv
  - Right Area 5 Medial Ventral
  - R_5mv
  - Cingulo-Opercular
  - R

* - R_6ma
  - Right Area 6ma
  - R_6ma
  - Cingulo-Opercular
  - R

* - R_6r
  - Right Premotor 6r
  - R_6r
  - Cingulo-Opercular
  - R

* - R_7Am
  - Right Area 7 Medial
  - R_7Am
  - Cingulo-Opercular
  - R

* - R_9-46d
  - R_9-46d
  - R_9-46d
  - Cingulo-Opercular
  - R

* - R_FEF
  - Right Frontal Eye Field
  - R_FEF
  - Cingulo-Opercular
  - R

* - R_FOP1
  - Right Frontal Opercular 1
  - R_FOP1
  - Cingulo-Opercular
  - R

* - R_FOP3
  - Right Frontal Opercular 3
  - R_FOP3
  - Cingulo-Opercular
  - R

* - R_FOP4
  - Right Frontal Opercular 4
  - R_FOP4
  - Cingulo-Opercular
  - R

* - R_FOP5
  - Right Frontal Opercular 5
  - R_FOP5
  - Cingulo-Opercular
  - R

* - R_IFSa
  - Right Inferior Frontal Sulcus Anterior
  - R_IFSa
  - Cingulo-Opercular
  - R

* - R_MI
  - Right Motor Insula
  - R_MI
  - Cingulo-Opercular
  - R

* - R_PEF
  - Right Parietal Eye Field
  - R_PEF
  - Cingulo-Opercular
  - R

* - R_PF
  - Right Prefrontal
  - R_PF
  - Cingulo-Opercular
  - R

* - R_PFcm
  - Right Prefrontal Cortex Medial
  - R_PFcm
  - Cingulo-Opercular
  - R

* - R_PFop
  - Right Prefrontal Opercular
  - R_PFop
  - Cingulo-Opercular
  - R

* - R_PI
  - Right Posterior Insula
  - R_PI
  - Cingulo-Opercular
  - R

* - R_PSL
  - Right Parietal Superior Lobule
  - R_PSL
  - Cingulo-Opercular
  - R

* - R_PoI1
  - Right Postcentral Insula 1
  - R_PoI1
  - Cingulo-Opercular
  - R

* - R_PoI2
  - Right Postcentral Insula 2
  - R_PoI2
  - Cingulo-Opercular
  - R

* - R_SCEF
  - Right Supplementary Cingulate Eye Field
  - R_SCEF
  - Cingulo-Opercular
  - R

* - R_a24pr
  - Right Anterior Cingulate 24pr
  - R_a24pr
  - Cingulo-Opercular
  - R

* - R_a32pr
  - R_a32pr
  - R_a32pr
  - Cingulo-Opercular
  - R

* - R_p24
  - Right Posterior Cingulate 24
  - R_p24
  - Cingulo-Opercular
  - R

* - R_p24pr
  - Right Posterior Cingulate 24pr
  - R_p24pr
  - Cingulo-Opercular
  - R

* - R_p32pr
  - Right Posterior Area 32pr
  - R_p32pr
  - Cingulo-Opercular
  - R

* - R_45
  - Right Area 45 (Broca)
  - R_45
  - Language
  - R

* - R_55b
  - Right Area 55b
  - R_55b
  - Language
  - R

* - R_A5
  - Right Auditory Area 5
  - R_A5
  - Language
  - R

* - R_IFJa
  - Right Inferior Frontal Junction Anterior
  - R_IFJa
  - Language
  - R

* - R_SFL
  - Right Superior Frontal Lobule
  - R_SFL
  - Language
  - R

* - R_STGa
  - Right Superior Temporal Gyrus Anterior
  - R_STGa
  - Language
  - R

* - R_STSdp
  - Right Superior Temporal Sulcus Dorsal Posterior
  - R_STSdp
  - Language
  - R

* - R_TGv
  - Right Temporal Gyrus Ventral
  - R_TGv
  - Language
  - R

* - R_TPOJ1
  - Right Temporo-Parietal Junction 1
  - R_TPOJ1
  - Language
  - R

* - R_11l
  - Right Area 11 Lateral
  - R_11l
  - Frontoparietal
  - R

* - R_13l
  - Right Area 13 Lateral (Insula)
  - R_13l
  - Frontoparietal
  - R

* - R_31a
  - Right Area 31 Anterior
  - R_31a
  - Frontoparietal
  - R

* - R_33pr
  - Right Area 33pr
  - R_33pr
  - Frontoparietal
  - R

* - R_44
  - Right Area 44 (Broca)
  - R_44
  - Frontoparietal
  - R

* - R_7Pm
  - Right Area 7 Posterior Medial
  - R_7Pm
  - Frontoparietal
  - R

* - R_8BM
  - Right Area 8BM
  - R_8BM
  - Frontoparietal
  - R

* - R_8C
  - Right Area 8C
  - R_8C
  - Frontoparietal
  - R

* - R_AVI
  - Right Anterior Ventral Insula
  - R_AVI
  - Frontoparietal
  - R

* - R_IFJp
  - Right Inferior Frontal Junction Posterior
  - R_IFJp
  - Frontoparietal
  - R

* - R_IFSp
  - Right Inferior Frontal Sulcus Posterior
  - R_IFSp
  - Frontoparietal
  - R

* - R_IP1
  - Right Intraparietal 1
  - R_IP1
  - Frontoparietal
  - R

* - R_IP2
  - Right Intraparietal 2
  - R_IP2
  - Frontoparietal
  - R

* - R_OFC
  - Right Orbitofrontal Cortex
  - R_OFC
  - Frontoparietal
  - R

* - R_PFm
  - Right Prefrontal Medial
  - R_PFm
  - Frontoparietal
  - R

* - R_POS2
  - Right Parieto-Occipital Sulcus 2
  - R_POS2
  - Frontoparietal
  - R

* - R_RSC
  - Right Retrosplenial Cortex
  - R_RSC
  - Frontoparietal
  - R

* - R_TE1m
  - Right Temporal Area 1m
  - R_TE1m
  - Frontoparietal
  - R

* - R_TE1p
  - Right Temporal Area 1p
  - R_TE1p
  - Frontoparietal
  - R

* - R_a10p
  - Right Area a10p
  - R_a10p
  - Frontoparietal
  - R

* - R_a47r
  - Right Area 47 Right
  - R_a47r
  - Frontoparietal
  - R

* - R_a9-46v
  - R_a9-46v
  - R_a9-46v
  - Frontoparietal
  - R

* - R_d32
  - Right Dorsal Area 32
  - R_d32
  - Frontoparietal
  - R

* - R_i6-8
  - R_i6-8
  - R_i6-8
  - Frontoparietal
  - R

* - R_p10p
  - Right Area p10p
  - R_p10p
  - Frontoparietal
  - R

* - R_p47r
  - Right Area p47r
  - R_p47r
  - Frontoparietal
  - R

* - R_p9-46v
  - R_p9-46v
  - R_p9-46v
  - Frontoparietal
  - R

* - R_s6-8
  - R_s6-8
  - R_s6-8
  - Frontoparietal
  - R

* - R_10d
  - Right Area 10 Dorsal
  - R_10d
  - Default
  - R

* - R_10pp
  - Right Area 10 Posterior Pole
  - R_10pp
  - Default
  - R

* - R_10r
  - Right Area 10 Rostral
  - R_10r
  - Default
  - R

* - R_10v
  - Right Area 10 Ventral
  - R_10v
  - Default
  - R

* - R_23d
  - Right Area 23 Dorsal
  - R_23d
  - Default
  - R

* - R_25
  - Right Area 25 (Subgenual)
  - R_25
  - Default
  - R

* - R_31pd
  - Right Area 31 Posterior Dorsal
  - R_31pd
  - Default
  - R

* - R_31pv
  - Right Area 31 Posterior Ventral
  - R_31pv
  - Default
  - R

* - R_47l
  - Right Area 47 Lateral
  - R_47l
  - Default
  - R

* - R_47m
  - R_47m
  - R_47m
  - Default
  - R

* - R_47s
  - Right Area 47 Superior
  - R_47s
  - Default
  - R

* - R_7m
  - Right Area 7 Medial
  - R_7m
  - Default
  - R

* - R_8Ad
  - Right Area 8A Dorsal
  - R_8Ad
  - Default
  - R

* - R_8Av
  - Right Area 8A Ventral
  - R_8Av
  - Default
  - R

* - R_8BL
  - Right Area 8B Lateral
  - R_8BL
  - Default
  - R

* - R_9a
  - Right Area 9a
  - R_9a
  - Default
  - R

* - R_9m
  - Right Area 9 Medial
  - R_9m
  - Default
  - R

* - R_9p
  - Right Area 9 Posterior
  - R_9p
  - Default
  - R

* - R_EC
  - Right Entorhinal Cortex
  - R_EC
  - Default
  - R

* - R_H
  - Right Hippocampus
  - R_H
  - Default
  - R

* - R_PGi
  - Right Posterior Gyrus Inferior
  - R_PGi
  - Default
  - R

* - R_PGs
  - Right Posterior Gyrus Superior
  - R_PGs
  - Default
  - R

* - R_PHA1
  - Right Parahippocampal 1
  - R_PHA1
  - Default
  - R

* - R_PHA2
  - Right Parahippocampal 2
  - R_PHA2
  - Default
  - R

* - R_POS1
  - Right Parieto-Occipital Sulcus 1
  - R_POS1
  - Default
  - R

* - R_PreS
  - Right Presubiculum
  - R_PreS
  - Default
  - R

* - R_STSda
  - Right Superior Temporal Sulcus Dorsal Anterior
  - R_STSda
  - Default
  - R

* - R_STSva
  - Right Superior Temporal Sulcus Ventral Anterior
  - R_STSva
  - Default
  - R

* - R_STSvp
  - Right Superior Temporal Sulcus Ventral Posterior
  - R_STSvp
  - Default
  - R

* - R_TE1a
  - Right Temporal Area 1a
  - R_TE1a
  - Default
  - R

* - R_TE2a
  - Right Temporal Area 2a
  - R_TE2a
  - Default
  - R

* - R_TGd
  - Right Temporal Gyrus Dorsal
  - R_TGd
  - Default
  - R

* - R_a24
  - Right Anterior Cingulate 24
  - R_a24
  - Default
  - R

* - R_d23ab
  - Right Area 23 Dorsal
  - R_d23ab
  - Default
  - R

* - R_p32
  - Right Posterior Area 32
  - R_p32
  - Default
  - R

* - R_s32
  - Right Superior Area 32
  - R_s32
  - Default
  - R

* - R_v23ab
  - Right Area 23 Ventral
  - R_v23ab
  - Default
  - R

* - R_PCV
  - Right Posterior Cingulate Ventral
  - R_PCV
  - Posterior-Multimodal
  - R

* - R_STV
  - Right Superior Temporal Ventral
  - R_STV
  - Posterior-Multimodal
  - R

* - R_TPOJ2
  - Right Temporo-Parietal Junction 2
  - R_TPOJ2
  - Posterior-Multimodal
  - R

* - R_TPOJ3
  - Right Temporo-Parietal Junction 3
  - R_TPOJ3
  - Posterior-Multimodal
  - R

* - R_AAIC
  - Right Anterior Agranular Insula
  - R_AAIC
  - Orbito-Affective
  - R

* - R_Pir
  - Right Piriform
  - R_Pir
  - Orbito-Affective
  - R

* - R_pOFC
  - Right Posterior Orbitofrontal Cortex
  - R_pOFC
  - Orbito-Affective
  - R

* - R-accumbens
  - Right Accumbens
  - accumbens_right
  - Subcortical
  - R

* - R-amygdala
  - Right Amygdala
  - amygdala_right
  - Subcortical
  - R

* - R-caudate
  - Right Caudate
  - caudate_right
  - Subcortical
  - R

* - R-cerebellum
  - Right Cerebellum
  - cerebellum_right
  - Subcortical
  - R

* - R-diencephalon
  - diencephalon_right
  - diencephalon_right
  - Subcortical
  - R

* - R-hippocampus
  - Right Hippocampus
  - hippocampus_right
  - Subcortical
  - R

* - R-pallidum
  - Right Pallidum
  - pallidum_right
  - Subcortical
  - R

* - R-putamen
  - Right Putamen
  - putamen_right
  - Subcortical
  - R

* - R-thalamus
  - Right Thalamus
  - thalamus_right
  - Subcortical
  - R
```

