 
% File parsed with ufo2mf (UFO to Metafont) by Simon Egli and Walter Egli  %



% box dimension definition %

beginfontchar("e", 10.02 + (incx * (10.02-10.02)), mean#, 0);


% einbauen : mean# aus Tabelle mit buchstaben gruppierungen link,;
% tabelle mit gruppierung: <glyph name="p" = mean# 
% tabelle mit gruppierung: <glyph name="A" = cap# 


 
% point coordinates font A

px7l := 8.97u ; py7l := 7.98u ;
px8l := 8.97u ; py8l := 6.4u ;
px8r := 6.49u ; py8r := 6.4u ;
px7r := 6.49u ; py7r := 8.37u ;
px6r := 4.96u ; py6r := 10.96u ;
px6l := 4.96u ; py6l := 12.97u ;
px3r := 4.96u ; py3r := 1.87u ;
px3l := 4.96u ; py3l := -0.14u ;
px4l := 0.86u ; py4l := 4.85u ;
px4r := 3.34u ; py4r := 4.46u ;
px5r := 3.34u ; py5r := 8.37u ;
px5l := 0.86u ; py5l := 7.98u ;
px10r := 7.79u ; py10r := 6.4u ;
px9r := 2.2u ; py9r := 6.4u ;
px9l := 2.2u ; py9l := 7.68u ;
px10l := 7.79u ; py10l := 7.68u ;
px2r := 6.58u ; py2r := 4.46u ;
px2l := 9.06u ; py2l := 4.85u ;
px1l := 9.06u ; py1l := 4.96u ;
px1r := 6.58u ; py1r := 4.96u ;

% reading mid points font A

.5(px8l + px8r) = x280;
.5(py8l + py8r) = y280;
.5(px7l + px7r) = x270;
.5(py7l + py7r) = y270;
.5(px6l + px6r) = x260;
.5(py6l + py6r) = y260;
.5(px3l + px3r) = x230;
.5(py3l + py3r) = y230;
.5(px4l + px4r) = x240;
.5(py4l + py4r) = y240;
.5(px5l + px5r) = x250;
.5(py5l + py5r) = y250;
.5(px10l + px10r) = x2100;
.5(py10l + py10r) = y2100;
.5(px9l + px9r) = x290;
.5(py9l + py9r) = y290;
.5(px2l + px2r) = x220;
.5(py2l + py2r) = y220;
.5(px1l + px1r) = x210;
.5(py1l + py1r) = y210;

% fake extra l an r for metafont

px8l = x8Bl; py8l = y8Bl; 
px8r = x8Br; py8r = y8Br; 
px7l = x7Bl; py7l = y7Bl; 
px7r = x7Br; py7r = y7Br; 
px6l = x6Bl; py6l = y6Bl; 
px6r = x6Br; py6r = y6Br; 
px3l = x3Bl; py3l = y3Bl; 
px3r = x3Br; py3r = y3Br; 
px4l = x4Bl; py4l = y4Bl; 
px4r = x4Br; py4r = y4Br; 
px5l = x5Bl; py5l = y5Bl; 
px5r = x5Br; py5r = y5Br; 
px10l = x10Bl; py10l = y10Bl; 
px10r = x10Br; py10r = y10Br; 
px9l = x9Bl; py9l = y9Bl; 
px9r = x9Br; py9r = y9Br; 
px2l = x2Bl; py2l = y2Bl; 
px2r = x2Br; py2r = y2Br; 
px1l = x1Bl; py1l = y1Bl; 
px1r = x1Br; py1r = y1Br; 

% pen width

dist8 := sqrt((y8Bl-y8Br) * (y8Bl-y8Br) + (x8Br-x8Bl) * (x8Br-x8Bl));
dist7 := sqrt((y7Bl-y7Br) * (y7Bl-y7Br) + (x7Br-x7Bl) * (x7Br-x7Bl));
dist6 := sqrt((y6Bl-y6Br) * (y6Bl-y6Br) + (x6Br-x6Bl) * (x6Br-x6Bl));
dist3 := sqrt((y3Bl-y3Br) * (y3Bl-y3Br) + (x3Br-x3Bl) * (x3Br-x3Bl));
dist4 := sqrt((y4Bl-y4Br) * (y4Bl-y4Br) + (x4Br-x4Bl) * (x4Br-x4Bl));
dist5 := sqrt((y5Bl-y5Br) * (y5Bl-y5Br) + (x5Br-x5Bl) * (x5Br-x5Bl));
dist10 := sqrt((y10Bl-y10Br) * (y10Bl-y10Br) + (x10Br-x10Bl) * (x10Br-x10Bl));
dist9 := sqrt((y9Bl-y9Br) * (y9Bl-y9Br) + (x9Br-x9Bl) * (x9Br-x9Bl));
dist2 := sqrt((y2Bl-y2Br) * (y2Bl-y2Br) + (x2Br-x2Bl) * (x2Br-x2Bl));
dist1 := sqrt((y1Bl-y1Br) * (y1Bl-y1Br) + (x1Br-x1Bl) * (x1Br-x1Bl));
 
% point coordinates font B

ppx7l := 8.97u ; ppy7l := 7.98u ;
ppx8l := 8.97u ; ppy8l := 6.4u ;
ppx8r := 6.49u ; ppy8r := 6.4u ;
ppx7r := 6.49u ; ppy7r := 8.37u ;
ppx6r := 4.96u ; ppy6r := 10.96u ;
ppx6l := 4.96u ; ppy6l := 12.97u ;
ppx3r := 4.96u ; ppy3r := 1.87u ;
ppx3l := 4.96u ; ppy3l := -0.14u ;
ppx4l := 0.86u ; ppy4l := 4.85u ;
ppx4r := 3.34u ; ppy4r := 4.46u ;
ppx5r := 3.34u ; ppy5r := 8.37u ;
ppx5l := 0.86u ; ppy5l := 7.98u ;
ppx10r := 7.79u ; ppy10r := 6.4u ;
ppx9r := 2.2u ; ppy9r := 6.4u ;
ppx9l := 2.2u ; ppy9l := 7.68u ;
ppx10l := 7.79u ; ppy10l := 7.68u ;
ppx2r := 6.58u ; ppy2r := 4.46u ;
ppx2l := 9.06u ; ppy2l := 4.85u ;
ppx1l := 9.06u ; ppy1l := 4.96u ;
ppx1r := 6.58u ; ppy1r := 4.96u ;

% reading mid points font B

.5(ppx8l + ppx8r) = x28A;
.5(ppy8l + ppy8r) = y28A;
.5(ppx7l + ppx7r) = x27A;
.5(ppy7l + ppy7r) = y27A;
.5(ppx6l + ppx6r) = x26A;
.5(ppy6l + ppy6r) = y26A;
.5(ppx3l + ppx3r) = x23A;
.5(ppy3l + ppy3r) = y23A;
.5(ppx4l + ppx4r) = x24A;
.5(ppy4l + ppy4r) = y24A;
.5(ppx5l + ppx5r) = x25A;
.5(ppy5l + ppy5r) = y25A;
.5(ppx10l + ppx10r) = x210A;
.5(ppy10l + ppy10r) = y210A;
.5(ppx9l + ppx9r) = x29A;
.5(ppy9l + ppy9r) = y29A;
.5(ppx2l + ppx2r) = x22A;
.5(ppy2l + ppy2r) = y22A;
.5(ppx1l + ppx1r) = x21A;
.5(ppy1l + ppy1r) = y21A;

% fake extra l an r for font B

ppx8l = x8Cl; ppy8l = y8Cl; 
ppx8r = x8Cr; ppy8r = y8Cr; 
ppx7l = x7Cl; ppy7l = y7Cl; 
ppx7r = x7Cr; ppy7r = y7Cr; 
ppx6l = x6Cl; ppy6l = y6Cl; 
ppx6r = x6Cr; ppy6r = y6Cr; 
ppx3l = x3Cl; ppy3l = y3Cl; 
ppx3r = x3Cr; ppy3r = y3Cr; 
ppx4l = x4Cl; ppy4l = y4Cl; 
ppx4r = x4Cr; ppy4r = y4Cr; 
ppx5l = x5Cl; ppy5l = y5Cl; 
ppx5r = x5Cr; ppy5r = y5Cr; 
ppx10l = x10Cl; ppy10l = y10Cl; 
ppx10r = x10Cr; ppy10r = y10Cr; 
ppx9l = x9Cl; ppy9l = y9Cl; 
ppx9r = x9Cr; ppy9r = y9Cr; 
ppx2l = x2Cl; ppy2l = y2Cl; 
ppx2r = x2Cr; ppy2r = y2Cr; 
ppx1l = x1Cl; ppy1l = y1Cl; 
ppx1r = x1Cr; ppy1r = y1Cr; 

% pen width Font B

dist8B := sqrt((y8Cl-y8Cr) * (y8Cl-y8Cr) + (x8Cr-x8Cl) * (x8Cr-x8Cl));
dist7B := sqrt((y7Cl-y7Cr) * (y7Cl-y7Cr) + (x7Cr-x7Cl) * (x7Cr-x7Cl));
dist6B := sqrt((y6Cl-y6Cr) * (y6Cl-y6Cr) + (x6Cr-x6Cl) * (x6Cr-x6Cl));
dist3B := sqrt((y3Cl-y3Cr) * (y3Cl-y3Cr) + (x3Cr-x3Cl) * (x3Cr-x3Cl));
dist4B := sqrt((y4Cl-y4Cr) * (y4Cl-y4Cr) + (x4Cr-x4Cl) * (x4Cr-x4Cl));
dist5B := sqrt((y5Cl-y5Cr) * (y5Cl-y5Cr) + (x5Cr-x5Cl) * (x5Cr-x5Cl));
dist10B := sqrt((y10Cl-y10Cr) * (y10Cl-y10Cr) + (x10Cr-x10Cl) * (x10Cr-x10Cl));
dist9B := sqrt((y9Cl-y9Cr) * (y9Cl-y9Cr) + (x9Cr-x9Cl) * (x9Cr-x9Cl));
dist2B := sqrt((y2Cl-y2Cr) * (y2Cl-y2Cr) + (x2Cr-x2Cl) * (x2Cr-x2Cl));
dist1B := sqrt((y1Cl-y1Cr) * (y1Cl-y1Cr) + (x1Cr-x1Cl) * (x1Cr-x1Cl));

% pen angle Font A

ang8 := angle((z8Br + (incx * (z8Cr -z8Br))) - (z8Bl + (incx * (z8Cl -z8Bl))));
ang7 := angle((z7Br + (incx * (z7Cr -z7Br))) - (z7Bl + (incx * (z7Cl -z7Bl))));
ang6 := angle((z6Br + (incx * (z6Cr -z6Br))) - (z6Bl + (incx * (z6Cl -z6Bl))));
ang3 := angle((z3Br + (incx * (z3Cr -z3Br))) - (z3Bl + (incx * (z3Cl -z3Bl))));
ang4 := angle((z4Br + (incx * (z4Cr -z4Br))) - (z4Bl + (incx * (z4Cl -z4Bl))));
ang5 := angle((z5Br + (incx * (z5Cr -z5Br))) - (z5Bl + (incx * (z5Cl -z5Bl))));
ang10 := angle((z10Br + (incx * (z10Cr -z10Br))) - (z10Bl + (incx * (z10Cl -z10Bl))));
ang9 := angle((z9Br + (incx * (z9Cr -z9Br))) - (z9Bl + (incx * (z9Cl -z9Bl))));
ang2 := angle((z2Br + (incx * (z2Cr -z2Br))) - (z2Bl + (incx * (z2Cl -z2Bl))));
ang1 := angle((z1Br + (incx * (z1Cr -z1Br))) - (z1Bl + (incx * (z1Cl -z1Bl))));

% center points and transformation

z8=(x280 + (incx * (x28A - x280)), y280 + (incx * (y28A - y280)));
z7=(x270 + (incx * (x27A - x270)), y270 + (incx * (y27A - y270)));
z6=(x260 + (incx * (x26A - x260)), y260 + (incx * (y26A - y260))) shifted (0,mean-y6l);
z3=(x230 + (incx * (x23A - x230)), y230 + (incx * (y23A - y230))) shifted (0,0-y3l);
z4=(x240 + (incx * (x24A - x240)), y240 + (incx * (y24A - y240)));
z5=(x250 + (incx * (x25A - x250)), y250 + (incx * (y25A - y250)));
z10=(x2100 + (incx * (x210A - x2100)), y2100 + (incx * (y210A - y2100)));
z9=(x290 + (incx * (x29A - x290)), y290 + (incx * (y29A - y290)));
z2=(x220 + (incx * (x22A - x220)), y220 + (incx * (y22A - y220)));
z1=(x210 + (incx * (x21A - x210)), y210 + (incx * (y21A - y210)));


% pen positions 

penpos8(dist8 + (incx * (px - dist8)), ang8);
penpos7(dist7 + (incx * (px - dist7)), ang7);
penpos6(dist6 + (incx * (px - dist6)), ang6);
penpos3(dist3 + (incx * (px - dist3)), ang3);
penpos4(dist4 + (incx * (px - dist4)), ang4);
penpos5(dist5 + (incx * (px - dist5)), ang5);
penpos10(dist10 + (incx * (px - dist10)), ang10);
penpos9(dist9 + (incx * (px - dist9)), ang9);
penpos2(dist2 + (incx * (px - dist2)), ang2);
penpos1(dist1 + (incx * (px - dist1)), ang1);



% pen strokes
 
penstroke  z1e -- 
super_ql(2e,3e, [0.707+ (incx * (0.707-0.707))]) ... 
super_qr(3e,4e, [0.707+ (incx * (0.707-0.707))]) ... 
 z4e -- 
super_ql(5e,6e, [0.707+ (incx * (0.707-0.707))]) ... 
super_qr(6e,7e, [0.707+ (incx * (0.707-0.707))]) ... 
 z7e -- 
 z8e;
penstroke  z9e shifted (0,y8r-y10r) ... z10e shifted (0,y8r-y10r);


% pen labels
penlabels(range 1 thru 99);
endchar;

