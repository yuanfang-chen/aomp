include ../Makefile.defs

TESTS_DIR = \
    DeclareSharedMemory \
    alignedattribute \
    ancestorC \
    aomp_mappings_newrt \
    assertok_error \
    atomic \
    atomic_double \
    CanonNE \
    clang-274983 \
    clang-262701 \
    clang-host-targ \
    clang-host-targ2 \
    clang-red-SglComplex \
    clang-red-DblComplex \
    clang-tracekernel \
    class \
    closed_bug2 \
    collapse \
    collapse-nonrectangle \
    complex \
    complex2 \
    d2h_slow_copy \
    data_enter_issue01 \
    data_issue_59 \
    data_share1 \
    data_share2 \
    decl_targ \
    declare_target_pointer \
    devices \
    devito_prob1 \
    extern_init \
    firstprivate \
    firstprivate2 \
    flags \
    famd-opt-279975 \
    flang-272328 \
    flang-272343 \
    flang-272343-2 \
    flang-273762 \
    flang-273990-2 \
    flang-274775-dcmplx \
    flang-275194-2 \
    flang-275194-3 \
    flang-275490 \
    flang-272285 \
    flang-272521 \
    flang-272534 \
    flang-272730-complex \
    flang-272878 \
    flang-273281 \
    flang-273284 \
    flang-274768 \
    flang-274775 \
    flang-274983 \
    flang-275194 \
    flang-275194-1 \
    flang_2regions \
    flang-atomic \
    flang_blkdata-g \
    flang_char_kind \
    flang_deviceio \
    flang_gen_sptr_prob \
    flang-host-targ \
    flang_isystem_prob \
    flang_klemm_map \
    flang_math \
    flang_omp_map \
    flang_omp_red_3d \
    flang_real16_prob \
    flang_reduction_offload \
    flang_red_swdev-273281 \
    flang_red_swdev-273281-spmd \
    flang_teams \
    flang_tgt_alloc_ptr \
    flang-tracekernel \
    fprintf \
    function \
    function_overload \
    function_template \
    gdb_teams \
    global_allocate \
    gpus \
    helloworld \
    hip_device_compile \
    hip_rocblas \
    host_targ \
    host_teams_numa_affinity \
    icvars-nest \
    icvars-nestF \
    issue_flang_libomp \
    issue_001 \
    issue_002 \
    kmpc_alloc \
    kokkos_log2 \
    launch_latency \
    liba_bundled \
    liba_bundled_cmdline \
    libgomp-292348 \
    longDouble \
    lto_teams \
    ManyKernels \
    map_to_from_prob \
    map_zero_bug \
    MasterBarrier \
    math_exp \
    math_flog \
    math_max \
    math_modff \
    math_pow \
    math_sqrt_float \
    matmul_fun \
    MaxNumThrds \
    mem_foot_print \
    memory_mgmt_routines \
    nativetests \
    nested_loop \
    nested_loop_trunk \
    nested_loop_trunk1 \
    nested_par3 \
    nested_targ \
    nest_call_par2 \
    omp_get_device_num \
    omp_get_initial \
    omp_lock \
    omp_num_teams_SPMD \
    omp_num_teams_generic \
    omp_places \
    omp_target_is \
    omp_targ_err1 \
    omp_wtime \
    pfspecifier \
    pfspecifier_str \
    printf_parallel_for_target \
    red_bug_51 \
    reduce \
    reduction \
    reduction_array_section \
    reduction_issue_16 \
    reduction_team \
    reduction_teams \
    reduction_teams_distribute_parallel \
    reduction_shared_array \
    reduc_map_prob \
    schedule \
    simd \
    simple_ctor \
    slices \
    snap_red \
    stream \
    targ-273742 \
    targc-273738 \
    targ_declare \
    target-in-other-source \
    targets_in_loop \
    task-helper \
    taskwait_prob \
    teams \
    teams_nest \
    teams_notarget \
    teams_notarget_get_num_teams \
    teams_notarget_get_team_num \
    team_prob \
    teams512-info \
    test \
    test_offload_macros \
    thread_limit\
    threads \
    Threads1xxx \
    unique-kernel-name \
    use_device_ptr \
    use_device_addr \
    vasp1 \
    veccopy \
    vmuldemo \
    vmulsum \
    wgs64 \
 bugz-50968 \
 clang-273738 \
 clang-273739 \
 clang-279673 \
 clang-282491-1 \
 clang-282491-3 \
 decl_map_targ \
 flang-273759 \
 flang-273805 \
 flang-273807 \
 flang-274775-critDcmplx \
 flang-274775-redDcmplx \
 flang-274983-2 \
 flang-278342 \
 flang-280342 \
 flang-288452 \
 flang-288613-2 \
 flang-288613-3 \
 flang-288613 \
 flang-288625 \
 flang-303839 \
 flang-cmplx-fib \
 flang-collapseNR \
 lds-prob1 \
 lds-prob2 \
 lds-prob3 \
 reduction_array \
 targc-274983 \
 virtfunc1 \
 clang-282491-2 \
 flang-273760 \
 flang-273959 \
 flang-289039 \
 flang-302472 \
 helloworld%n \
 targc-272328 \
 alloc_cgroup \
 clang-310865 \
 clang-310866 \
 clang-313307_simple_arr \
 clang-313307_simple_spmd \
 clang-323972 \
 clang-gdb1 \
 clang-gfx1030 \
 clang-ifaces \
 clang_udel_saxpy \
 complex-debug \
 complex_reduction \
 const_global_ctor-308039 \
 data-env-scalar-map \
 dominik-AD \
 flang-270386 \
 flang-274775-1 \
 flang-275194 \
 flang-275194-4 \
 flang-288160 \
 flang-288446 \
 flang-303839 \
 flang-307433 \
 flang-307434 \
 flang-308205 \
 flang-312148 \
 flang-312594 \
 flang-313307 \
 flang-313307_simple_arr \
 flang-313307_simple_generic \
 flang-313307_simple_spmd \
 flang-314146 \
 flang-315421 \
 flang-315870 \
 flang-319356 \
 flang-321277 \
 flang-321277-2 \
 flang-321412 \
 flang-321847 \
 flang-322945 \
 flang-325322 \
 flang-ifaces \
 flang-teams1 \
 flang-teams-gdb \
 flang-usm \
 func-ptr \
 leopold-devicePtr \
 loop_order \
 MasterBarrierO0 \
 omp_loop \
 requires_usm \
 targc-generic \
 targc-spmd \
 usm1 \
 usm-globals \
 usm-globals-with-pragma \
 usm-locals-xnack-disabled-xnack-any \
 usm-locals-xnack-disabled-xnack-minus \
 usm-locals-xnack-disabled-xnack-plus \
 usm-locals-xnack-disabled-xnack-any-apu-maps \
 usm-locals-xnack-enabled-xnack-any-apu \
 usm-locals-xnack-enabled-xnack-any-apu-maps-non-apu \
 usm-locals-xnack-enabled-xnack-any-non-apu \
 usm-locals-xnack-enabled-xnack-minus \
 usm-locals-xnack-enabled-xnack-plus-apu \
 usm-locals-xnack-enabled-xnack-plus-apu-maps-non-apu \
 usm-locals-xnack-enabled-xnack-plus-non-apu \
 usm-locals-pragma-xnack-disabled-xnack-any \
 usm-locals-pragma-xnack-disabled-xnack-minus \
 usm-locals-pragma-xnack-disabled-xnack-plus \
 usm-locals-pragma-xnack-enabled-xnack-any \
 usm-locals-pragma-xnack-enabled-xnack-minus \
 usm-locals-pragma-xnack-enabled-xnack-plus \
 veccopy-ompt-target \
 veccopy-ompt-target-disallow-both \
 veccopy-ompt-target-emi \
 veccopy-ompt-target-emi-map \
 veccopy-ompt-target-emi-tracing \
 veccopy-ompt-target-map \
 veccopy-ompt-target-noinit \
 veccopy-ompt-target-tracing \
 veccopy-ompt-target-wrong-return \
 vmulsum-hsa-stats \
 workgroup_size


all:
	@for test_dir in $(TESTS_DIR); do \
	  echo; \
	  test_name=`grep "TESTNAME *=" $$test_dir/Makefile | sed "s/.*= *//"`; \
	  echo "TEST_DIR: $$test_dir\tTEST_NAME: $$test_name\tMAKE: $(MAKE) -C $$test_dir"; \
	  $(MAKE) -C $$test_dir; \
	done

run run_obin run_sbin run_llbin clean clean_log llbin sbin obin:
	@for test_dir in $(TESTS_DIR); do \
	  echo $$nnn; \
	  test_name=`grep "TESTNAME *=" $$test_dir/Makefile | sed "s/.*= *//"`; \
	  echo "TEST_DIR: $$test_dir\tTEST_NAME: $$test_name\tMAKE: $(MAKE) -C $$test_dir $@"; \
	  $(MAKE) -C $$test_dir $@; \
	done

check:
	 @for test_dir in $(TESTS_DIR); do \
          echo $$nnn; \
          test_name=`grep "TESTNAME *=" $$test_dir/Makefile | sed "s/.*= *//"`; \
          echo "TEST_DIR: $$test_dir\tTEST_NAME: $$test_name\tMAKE: $(MAKE) -C $$test_dir $@"; \
          $(MAKE) -C $$test_dir $@; \
        done

.ll .ll.s .ll.o .s .s.o .o:
	@for test_dir in $(TESTS_DIR); do \
	  echo $$nnn; \
	  test_name=`grep "TESTNAME *=" $$test_dir/Makefile | sed "s/.*= *//"`; \
	  echo "TEST_DIR: $$test_dir\tTEST_NAME: $$test_name\tMAKE: $(MAKE) -C $$test_dir $$test_name$@"; \
	  $(MAKE) -C $$test_dir $$test_name$@; \
	done

help:
	@echo 
	@echo "LLVM Tool Chain:	$(AOMP)/bin"
	@echo "Offload Targets:	$(TARGET)"
	@echo "Host Target:		$(AOMP_CPUTARGET)"
	@echo "Application Dirs:	$(TESTS_DIR)"
	@echo 
	@echo "This Makefile supports the following flags:"
	@echo 
	@echo "	make llbin      // Link pass only"
	@echo "	make run_llbin  // Execute llbin"
	@echo 
	@echo "	make sbin       // Link pass only"
	@echo "	make run_sbin   // Execute sbin"
	@echo 
	@echo "	make obin       // Link pass only"
	@echo "	make run_obin   // Execute obin"
	@echo 
	@echo "	make .ll        // Compile pass only             : -c -S -emit-llvm"
	@echo "	make .ll.s      // Backend pass only             : -c -S"
	@echo "	make .ll.o      // Assemble pass only            : -c"
	@echo "	make .s         // Compile & Backend passes      : -c -S"
	@echo "	make .s.o       // Assemble pass only            : -c"
	@echo "	make .o         // Compile, Backend, Assemble    : -c"
	@echo 
	@echo "	make            // All passes, build all examples from Application Dirs"
	@echo "	make run        // Execute all binaries from Application Dirs"
	@echo 
	@echo "	make clean"
	@echo "	make clean_log"
	@echo "	make help"
	@echo 
	@echo " Environment variables to control compilation & execution"
	@echo "    VERBOSE=1        See lots of compiler messages and driver actions"
	@echo "    TEMPS=1          Do not delete intermediate files"
	@echo "    OFFLOAD_DEBUG=1  See Runtime diagnostics for each call to libomptarget API"
	@echo "    TARGET=          Override Makefile target"
	@echo
	@echo " Compile Environment:  $(SETENV)"
	@echo
	@echo " Run Environment:      $(RUNENV)"
	@echo
	@echo " Compile Flags:        $(CFLAGS) $(EXTRA_CFLAGS)"
	@echo
	@echo " OMP Compile Flags:    $(OMP_FLAGS) $(EXTRA_OMP_FLAGS)"
	@echo
	@echo " Link Flags:           $(LINK_FLAGS) $(EXTRA_LDFLAGS)"
	@echo
