target_sources(
                metgrid
                PRIVATE
                  cio.c
                  wrf_debug.F
                  bitarray_module.F
                  constants_module.F
                  datatype_module.F
                  module_stringutil.F
                  gridinfo_module.F
                  metgrid.F
                  input_module.F
                  interp_module.F
                  interp_option_module.F
                  list_module.F
                  llxy_module.F
                  met_data_module.F
                  minheap_module.F
                  misc_definitions_module.F
                  module_date_pack.F
                  module_debug.F
                  module_map_utils.F
                  module_mergesort.F
                  output_module.F
                  parallel_module.F
                  process_domain_module.F
                  queue_module.F
                  read_met_module.F
                  rotate_winds_module.F
                  storage_module.F
                  write_met_module.F
                  scan_input.F
                  mpas_mesh.F
                  target_mesh.F
                  remapper.F
                )