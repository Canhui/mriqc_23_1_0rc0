Node: anatMRIQC (ComputeIQMs (measures (anatomical)
===================================================


 Hierarchy : mriqc_wf.anatMRIQC.ComputeIQMs.measures
 Exec ID : measures.a0


Original Inputs
---------------


* air_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/ArtifactMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_air.nii.gz
* artifact_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/ArtifactMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_art.nii.gz
* head_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/HeadMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/fsl_bet/clipped_corrected_brain_outskin_mask.nii.gz
* human : True
* in_bias : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/synthstrip_wf/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/post_n4/clipped_bias.nii.gz
* in_file : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/conform/sub-C001_acq-MP2RAGE_run-01_T1w_conformed.nii.gz
* in_fwhm : [0.0, 0.0, 0.0]
* in_noinu : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/harmonize/clipped_corrected_harmonized.nii.gz
* in_pvms : ['/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_0.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_1.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_2.nii.gz']
* in_segm : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_seg.nii.gz
* in_tpms : <undefined>
* mni_tpms : ['/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t10/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg_trans.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t11/tpl-MNI152NLin2009cAsym_res-01_label-GM_probseg_trans.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t12/tpl-MNI152NLin2009cAsym_res-01_label-WM_probseg_trans.nii.gz']
* rot_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/RotationMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_rotmask.nii.gz


Execution Inputs
----------------


* air_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/ArtifactMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_air.nii.gz
* artifact_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/ArtifactMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_art.nii.gz
* head_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/HeadMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/fsl_bet/clipped_corrected_brain_outskin_mask.nii.gz
* human : True
* in_bias : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/synthstrip_wf/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/post_n4/clipped_bias.nii.gz
* in_file : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/conform/sub-C001_acq-MP2RAGE_run-01_T1w_conformed.nii.gz
* in_fwhm : [0.0, 0.0, 0.0]
* in_noinu : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/harmonize/clipped_corrected_harmonized.nii.gz
* in_pvms : ['/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_0.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_1.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_pve_2.nii.gz']
* in_segm : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/segmentation/segment_seg.nii.gz
* in_tpms : <undefined>
* mni_tpms : ['/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t10/tpl-MNI152NLin2009cAsym_res-01_label-CSF_probseg_trans.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t11/tpl-MNI152NLin2009cAsym_res-01_label-GM_probseg_trans.nii.gz', '/home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/MNItpms2t1/mapflow/_MNItpms2t12/tpl-MNI152NLin2009cAsym_res-01_label-WM_probseg_trans.nii.gz']
* rot_msk : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/AirMaskWorkflow/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/RotationMask/sub-C001_acq-MP2RAGE_run-01_T1w_conformed_rotmask.nii.gz


Execution Outputs
-----------------


* cjv : <undefined>
* cnr : <undefined>
* efc : <undefined>
* fber : <undefined>
* fwhm : <undefined>
* icvs : <undefined>
* inu : <undefined>
* out_noisefit : <undefined>
* out_qc : {'summary_csf_mean': 62.92230774801576, 'summary_csf_stdv': 73.289225592603, 'summary_csf_median': 36.34220635518432, 'summary_csf_mad': 26.212395778824966, 'summary_csf_p95': 208.5312994312494, 'summary_csf_p05': 14.536882542073727, 'summary_csf_k': 17.164570835230737, 'summary_csf_n': 17214.0, 'summary_gm_mean': 480.5945639839447, 'summary_gm_stdv': 110.57242009164302, 'summary_gm_median': 476.79852198809385, 'summary_gm_mad': 119.28720428236696, 'summary_gm_p95': 657.8949635561556, 'summary_gm_p05': 304.9574160616845, 'summary_gm_k': -0.13613138146910408, 'summary_gm_n': 4935.0, 'summary_wm_mean': 995.6562481286812, 'summary_wm_stdv': 70.39751239772646, 'summary_wm_median': 1000.0140395835042, 'summary_wm_mad': 31.538088889443372, 'summary_wm_p95': 1050.8229697812349, 'summary_wm_p05': 888.4336438551545, 'summary_wm_k': 19.720814546489734, 'summary_wm_n': 32411.0, 'summary_bg_mean': 0.0, 'summary_bg_median': 0.0, 'summary_bg_p95': 0.0, 'summary_bg_p05': 0.0, 'summary_bg_k': 0.0, 'summary_bg_stdv': 0.0, 'summary_bg_mad': 0.0, 'summary_bg_n': 0.0, 'snr_csf': 0.49585939059565737, 'snr_wm': 14.205027682469144, 'snr_gm': 4.311655757296454, 'snr_total': 6.337514276787085, 'snrd_csf': -1.0, 'snrd_wm': -1.0, 'snrd_gm': -1.0, 'snrd_total': -1.0, 'cnr': 3.9915619675345524, 'fber': 618.5123986507238, 'efc': 0.5696831310663963, 'wm2max': 0.6021696968078716, 'qi_1': -1.0, 'cjv': 0.2882660932247805, 'fwhm_x': 0.0, 'fwhm_y': 0.0, 'fwhm_z': 0.0, 'fwhm_avg': 0.0, 'icvs_csf': 0.2531237210899946, 'icvs_gm': 0.4272930711773794, 'icvs_wm': 0.319583207732626, 'rpve_csf': 9.394146836997194, 'rpve_gm': 5.243900964583361, 'rpve_wm': 8.24990914256172, 'size_x': 56, 'size_y': 171, 'size_z': 171, 'spacing_x': 0.7000045776367188, 'spacing_y': 0.7017543911933899, 'spacing_z': 0.7017543911933899, 'inu_range': 0.1530226469039917, 'inu_med': 0.6355405449867249, 'tpm_overlap_csf': 0.08452203724481609, 'tpm_overlap_gm': 0.14401270880284445, 'tpm_overlap_wm': 0.08180732433004496}
* qi_1 : <undefined>
* rpve : <undefined>
* size : <undefined>
* snr : <undefined>
* snrd : <undefined>
* spacing : <undefined>
* summary : <undefined>
* tpm_overlap : <undefined>
* wm2max : <undefined>


Runtime info
------------


* duration : 0.917265
* hostname : ubuntu
* prev_wd : /home/joe/mriqc_space/mriqc23.1.0rc0
* working_dir : /home/joe/mriqc_space/mriqc23.1.0rc0/work/mriqc_wf/anatMRIQC/ComputeIQMs/_in_file_..home..joe..mriqc_space..sub-C001..anat..sub-C001_acq-MP2RAGE_run-01_T1w.nii.gz/measures


Environment
~~~~~~~~~~~


* AFNI_DIR : /home/joe/dependency/afni
* AFNI_IMSAVE_WARNINGS : NO
* AFNI_MODELPATH : /home/joe/dependency/afni/models
* AFNI_PLUGINPATH : /home/joe/dependency/afni/plugins
* AFNI_TTATLAS_DATASET : /home/joe/dependency/afni/atlases
* ANTSPATH : /home/joe/dependency/ants
* COLORTERM : truecolor
* CONDA_DEFAULT_ENV : df_to_conda
* CONDA_EXE : /home/joe/miniconda3/bin/conda
* CONDA_PATH : /home/joe/miniconda3
* CONDA_PREFIX : /home/joe/miniconda3/envs/df_to_conda
* CONDA_PROMPT_MODIFIER : (df_to_conda) 
* CONDA_PYTHON_EXE : /home/joe/miniconda3/bin/python
* CONDA_SHLVL : 1
* DBUS_SESSION_BUS_ADDRESS : unix:path=/run/user/1000/bus
* DESKTOP_SESSION : ubuntu
* DISPLAY : :1
* FREESURFER_HOME : /home/joe/dependency/freesurfer
* FSLDIR : /home/joe/dependency/fsl
* FSLGECUDAQ : cuda.q
* FSLOUTPUTTYPE : NIFTI_GZ
* FSLTCLSH : /home/joe/dependency/fsl/bin/fsltclsh
* FSLWISH : /home/joe/dependency/fsl/bin/fslwish
* GDMSESSION : ubuntu
* GNOME_DESKTOP_SESSION_ID : this-is-deprecated
* GNOME_SHELL_SESSION_MODE : ubuntu
* GNOME_TERMINAL_SCREEN : /org/gnome/Terminal/screen/c10f19d3_27cb_4093_ab08_44ca3ed8a9d9
* GNOME_TERMINAL_SERVICE : :1.96
* GPG_AGENT_INFO : /run/user/1000/gnupg/S.gpg-agent:0:1
* GTK_MODULES : gail:atk-bridge
* HOME : /home/joe
* IM_CONFIG_PHASE : 1
* INVOCATION_ID : eb1cdaf32e9c402c8db15d35e9eca69d
* IS_DOCKER_8395080871 : 1
* JOURNAL_STREAM : 8:42551
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : en_HK.UTF-8
* LANGUAGE : en_HK:en
* LESSCLOSE : /usr/bin/lesspipe %s %s
* LESSOPEN : | /usr/bin/lesspipe %s
* LOGNAME : joe
* LS_COLORS : rs=0:di=01;34:ln=01;36:mh=00:pi=40;33:so=01;35:do=01;35:bd=40;33;01:cd=40;33;01:or=40;31;01:mi=00:su=37;41:sg=30;43:ca=30;41:tw=30;42:ow=34;42:st=37;44:ex=01;32:*.tar=01;31:*.tgz=01;31:*.arc=01;31:*.arj=01;31:*.taz=01;31:*.lha=01;31:*.lz4=01;31:*.lzh=01;31:*.lzma=01;31:*.tlz=01;31:*.txz=01;31:*.tzo=01;31:*.t7z=01;31:*.zip=01;31:*.z=01;31:*.dz=01;31:*.gz=01;31:*.lrz=01;31:*.lz=01;31:*.lzo=01;31:*.xz=01;31:*.zst=01;31:*.tzst=01;31:*.bz2=01;31:*.bz=01;31:*.tbz=01;31:*.tbz2=01;31:*.tz=01;31:*.deb=01;31:*.rpm=01;31:*.jar=01;31:*.war=01;31:*.ear=01;31:*.sar=01;31:*.rar=01;31:*.alz=01;31:*.ace=01;31:*.zoo=01;31:*.cpio=01;31:*.7z=01;31:*.rz=01;31:*.cab=01;31:*.wim=01;31:*.swm=01;31:*.dwm=01;31:*.esd=01;31:*.jpg=01;35:*.jpeg=01;35:*.mjpg=01;35:*.mjpeg=01;35:*.gif=01;35:*.bmp=01;35:*.pbm=01;35:*.pgm=01;35:*.ppm=01;35:*.tga=01;35:*.xbm=01;35:*.xpm=01;35:*.tif=01;35:*.tiff=01;35:*.png=01;35:*.svg=01;35:*.svgz=01;35:*.mng=01;35:*.pcx=01;35:*.mov=01;35:*.mpg=01;35:*.mpeg=01;35:*.m2v=01;35:*.mkv=01;35:*.webm=01;35:*.ogm=01;35:*.mp4=01;35:*.m4v=01;35:*.mp4v=01;35:*.vob=01;35:*.qt=01;35:*.nuv=01;35:*.wmv=01;35:*.asf=01;35:*.rm=01;35:*.rmvb=01;35:*.flc=01;35:*.avi=01;35:*.fli=01;35:*.flv=01;35:*.gl=01;35:*.dl=01;35:*.xcf=01;35:*.xwd=01;35:*.yuv=01;35:*.cgm=01;35:*.emf=01;35:*.ogv=01;35:*.ogx=01;35:*.aac=00;36:*.au=00;36:*.flac=00;36:*.m4a=00;36:*.mid=00;36:*.midi=00;36:*.mka=00;36:*.mp3=00;36:*.mpc=00;36:*.ogg=00;36:*.ra=00;36:*.wav=00;36:*.oga=00;36:*.opus=00;36:*.spx=00;36:*.xspf=00;36:
* MANAGERPID : 1632
* MKL_NUM_THREADS : 1
* NIPYPE_NO_ET : 1
* NO_ET : 1
* OLDPWD : /home/joe/mriqc_space
* OMP_NUM_THREADS : 1
* PATH : /home/joe/miniconda3/envs/df_to_conda/bin:/home/joe/miniconda3/condabin:/home/joe/.local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/home/joe/dependency/ants:/home/joe/dependency/fsl/bin:/home/joe/dependency/fsl:/home/joe/dependency/afni:/home/joe/dependency/ants:/home/joe/dependency/fsl/bin:/home/joe/dependency/fsl:/home/joe/dependency/freesurfer/bin:/home/joe/dependency/fsl/bin
* POSSUMDIR : /home/joe/dependency/fsl
* PWD : /home/joe/mriqc_space/mriqc23.1.0rc0
* PYTHONWARNINGS : ignore
* QT_ACCESSIBILITY : 1
* QT_IM_MODULE : ibus
* SESSION_MANAGER : local/ubuntu:@/tmp/.ICE-unix/1898,unix/ubuntu:/tmp/.ICE-unix/1898
* SETUPTOOLS_SCM_PRETEND_VERSION : 1
* SHELL : /bin/bash
* SHLVL : 1
* SSH_AGENT_PID : 1862
* SSH_AUTH_SOCK : /run/user/1000/keyring/ssh
* TERM : xterm-256color
* USER : joe
* USERNAME : joe
* VTE_VERSION : 6003
* WINDOWPATH : 2
* XAUTHORITY : /run/user/1000/gdm/Xauthority
* XDG_CONFIG_DIRS : /etc/xdg/xdg-ubuntu:/etc/xdg
* XDG_CURRENT_DESKTOP : ubuntu:GNOME
* XDG_DATA_DIRS : /usr/share/ubuntu:/usr/local/share/:/usr/share/:/var/lib/snapd/desktop
* XDG_MENU_PREFIX : gnome-
* XDG_RUNTIME_DIR : /run/user/1000
* XDG_SESSION_CLASS : user
* XDG_SESSION_DESKTOP : ubuntu
* XDG_SESSION_TYPE : x11
* XMODIFIERS : @im=ibus
* _ : /home/joe/miniconda3/envs/df_to_conda/bin/python
* _CE_CONDA : 
* _CE_M : 

