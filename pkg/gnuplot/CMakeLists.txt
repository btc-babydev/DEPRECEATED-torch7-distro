SET(src)
SET(luasrc init.lua gnuplot.lua hist.lua)
  
ADD_TORCH_PACKAGE(gnuplot "${src}" "${luasrc}")
ADD_TORCH_DOK(dok gnuplot "Fundamentals" "Plotting with Gnuplot" 1.3)
