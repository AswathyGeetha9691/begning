# begning
function shp=Shapf(xi,eta)
    shp(1)= 0.25*(1-xi)*(1-eta);
    shp(2)= 0.25*(1+xi)*(1-eta);
    shp(3)= 0.25*(1+xi)*(1+eta);
    shp(4)= 0.25*(1-xi)*(1+eta);
end
