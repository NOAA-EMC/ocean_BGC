list ( APPEND _files
pkg/ocean_BGC/mocsy/src/mocsy_vars.F90
pkg/ocean_BGC/mocsy/src/mocsy_phsolvers.F90
pkg/ocean_BGC/mocsy/src/mocsy_singledouble.F90
pkg/ocean_BGC/mocsy/src/mocsy_rho.F90
pkg/ocean_BGC/mocsy/src/mocsy_sw_ptmp.F90
pkg/ocean_BGC/mocsy/src/kind_map_s
pkg/ocean_BGC/mocsy/src/mocsy_sw_adtg.F90
pkg/ocean_BGC/mocsy/src/kind_map_d
pkg/ocean_BGC/mocsy/src/mocsy_varsolver.F90
pkg/ocean_BGC/mocsy/src/mocsy_DNAD.F90
pkg/ocean_BGC/mocsy/src/mocsy_p80.F90
pkg/ocean_BGC/mocsy/src/kind_map
pkg/ocean_BGC/mocsy/src/mocsy_constants.F90
pkg/ocean_BGC/mocsy/src/mocsy_sw_temp.F90
pkg/ocean_BGC/generic_tracers/FMS_ocmip2_co2calc.F90
pkg/ocean_BGC/generic_tracers/generic_BLING.F90
pkg/ocean_BGC/generic_tracers/generic_age.F90
pkg/ocean_BGC/generic_tracers/generic_miniBLING.F90
pkg/ocean_BGC/generic_tracers/generic_TOPAZ.F90
pkg/ocean_BGC/generic_tracers/generic_COBALT.F90
pkg/ocean_BGC/generic_tracers/FMS_coupler_util.F90
pkg/ocean_BGC/generic_tracers/generic_tracer.F90
pkg/ocean_BGC/generic_tracers/generic_tracer_utils.F90
)

set ( ocean_bgc_src_files
      ${_files}
      PARENT_SCOPE
)
