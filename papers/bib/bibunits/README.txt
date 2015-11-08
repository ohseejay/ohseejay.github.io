Abstract

  The `bibunits' package allows separate bibliographies for different
  units or parts of the text. The units can be chapters, sections or
  bibunit environments. The package is compatible with a wide variety of
  packages, including, but not limited to, natbib, overcite and
  KOMA-SCRIPT classes.


To produce the style
  
  latex bibunits.ins


To produce the documentation

  latex bibunits.dtx

  If you also want to include the macro section in the documentation,
  comment out \OnlyDescription.

  To produce an index for the documentation:

    makeindex -s gind.ist bibunits

  To produce a change history for the documentation:
  
    makeindex -s gglo.ist -o bibunits.gls bibunits.glo



Happy TeXing

  Thorsten Hansen, hansen@neuro.informatik.uni-ulm.de