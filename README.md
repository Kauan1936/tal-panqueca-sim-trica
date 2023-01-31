# tyrarush {
    "header" : {
        "file_version" : 41,
        "format_version" : 1,
        "library_version" : 1
    },
    "profiles" : {
        "ColorCorrection" : {
            "defaults" : [
                {
                    "Default" : [
                        [
                            "CC_Tags",
                            ""
                        ]
                    ]
                }
            ],
            "selection" : [
                
            ],
            "overrides" : [
                
            ],
            "priority" : [
                
            ]
        },
        "CPU" : {
            "defaults" : [
                {
                    "Default" : [
                        [
                            "UseLessBananaSounds",
                            false,
                            "Will use a different event for bananas",
                            "[;]"
                        ],
                        [
                            "UseLessSounds",
                            true,
                            "Will use a different event for bananas",
                            "[;]"
                        ],
                        [
                            "CPU_Level",
                            1,
                            "Level of CPU",
                            "[0;2]"
                        ]
                    ]
                }
            ],
            "selection" : [
                {
                    "CPU_Low" : [
                        [
                            [
                                "CORES<2"
                            ]
                        ]
                    ]
                },
                {
                    "CPU_Medium" : [
                        [
                            [
                                "CORES=2"
                            ],
                            [
                                "CPUFMAX<1200000"
                            ]
                        ]
                    ]
                },
                {
                    "CPU_High" : [
                        [
                            [
                                "CORES=2"
                            ],
                            [
                                "CPUFMAX>=1200000"
                            ]
                        ],
                        [
                            [
                                "CORES>2"
                            ]
                        ]
                    ]
                }
            ],
            "overrides" : {
                "CPU_High" : {
                    "UseLessSounds" : false,
                    "CPU_Level" : 2
                },
                "CPU_Low" : {
                    "UseLessBananaSounds" : true,
                    "CPU_Level" : 0
                },
                "CPU_Medium" : {
                    "UseLessBananaSounds" : true
                }
            },
            "priority" : [
                
            ]
        },
        "GPU" : {
            "defaults" : [
                {
                    "Default" : [
                        [
                            "GPU_Level",
                            3,
                            "GPU level",
                            "[0;5]"
                        ],
                        [
                            "HideOptionalDecos",
                            false,
                            "Enable for lowend platforms, will hide deocos marked as optional ",
                            "[;]"
                        ],
                        [
                            "ShowAllRecommendedCostumesInMilestone",
                            true,
                            "Must show all recommended costumes in milestone screen?",
                            "[;]"
                        ],
                        [
                            "UseBarla",
                            true,
                            "Use BARLA in shaders",
                            "[;]"
                        ],
                        [
                            "UseCurvature",
                            true,
                            "Use curvature in shaders",
                            "[;]"
                        ],
                        [
                            "UseNdis",
                            true,
                            "Use NDIS in shaders, specular reflections",
                            "[;]"
                        ],
                        [
                            "UseIngameUITextEffect",
                            true,
                            "Ingame UI text effects for bananas and score",
                            "[;]"
                        ],
                        [
                            "UseLinearSpace",
                            true,
                            "Use linear space in shaders",
                            "[;]"
                        ],
                        [
                            "UseLowMaterials",
                            false,
                            "Enable  for low end platforms ",
                            "[;]"
                        ],
                        [
                            "UseLowModels",
                            false,
                            "If paramater is set in clara will use a different model ",
                            "[;]"
                        ],
                        [
                            "UseLowParticles",
                            false,
                            "If paramater is set in clara will use a different particle emitter",
                            "[;]"
                        ],
                        [
                            "UsePostFX",
                            false,
                            "Use Post FX",
                            "[;]"
                        ],
                        [
                            "UseSpecularLight",
                            true,
                            "Use specular light in shaders",
                            "[;]"
                        ],
                        [
                            "UseSpecularMask",
                            true,
                            "Use specular mask ",
                            "[;]"
                        ],
                        [
                            "UseUIDespicableScoreParticles",
                            true,
                            "When performing a despicable action, is the text accompanied by particles",
                            "[;]"
                        ],
                        [
                            "UseRimLight",
                            false,
                            "Use rim light in shaders",
                            "[;]"
                        ],
                        [
                            "MaxOutline",
                            -1,
                            "ms limit the interface text outline for igtitlemgr and despicable bonus text",
                            "[-1;1]"
                        ],
                        [
                            "PlatformPriority",
                            5,
                            "Used to know if a Deco3D must be show or not in a platform",
                            "[0;10]"
                        ],
                        [
                            "TextureStartLOD",
                            0,
                            "0 means max quality, 1 means half, 2 means quarter",
                            "[0;2]"
                        ],
                        [
                            "UseShadows",
                            3,
                            "0 - None, 1 - Low Res, 2 - Med Res, 3 - High Res, 4 - Ultra High Res",
                            "[0;4]"
                        ],
                        [
                            "BackgroundFarPlane",
                            600.0,
                            "Far distance clipping plane for background objects ",
                            "[0;1000]"
                        ],
                        [
                            "DecosAnimationRadius",
                            100.0,
                            "Decos that are Closer then this are animated ",
                            "[0;200]"
                        ],
                        [
                            "DecoGenerationGroupAllowedDecosLerp",
                            0.7,
                            "Use on deco generation groups between minAllowed decos and maxAllowed decos",
                            "[0;1]"
                        ],
                        [
                            "DownsamplePercent",
                            0.0,
                            "Render into a smaller resolutiuon ",
                            "[0;1]"
                        ],
                        [
                            "MapCamera_maxVisibilityOffsetBehind",
                            0.0,
                            "Map camera max visibilities offsets",
                            "[0;20]"
                        ],
                        [
                            "MapCamera_maxVisibilityOffsetFront",
                            43.0,
                            "Map camera max visibilities offsets",
                            "[0;50]"
                        ],
                        [
                            "SceneMgrCullingRadius",
                            10.0,
                            "Will not draw objects that smaller then radius",
                            "[0;100]"
                        ],
                        [
                            "SceneMgrCullingDistance",
                            90.0,
                            "Will not draw objects that are further then distance",
                            "[0;200]"
                        ],
                        [
                            "SceneMgrCullingScreenPixels",
                            3.0,
                            "Will not draw objects that smaller then this number of pixels on screen",
                            "[0;10]"
                        ],
                        [
                            "SynchronizedObjectDistance",
                            40.0,
                            "Synchronized object distance (lower causes popping but may increase fps)",
                            "[0;100]"
                        ],
                        [
                            "UseEmissiveness",
                            true,
                            "Use Emissiveness in shaders",
                            "[;]"
                        ],
                        [
                            "ForceRoadShader",
                            true,
                            "Force Road Shader",
                            "[;]"
                        ],
                        [
                            "MsaaEnum",
                            1,
                            "msaa level: 0 for no msaa",
                            "[0;2]"
                        ]
                    ]
                }
            ],
            "selection" : [
                {
                    "GPU_5" : [
                        [
                            [
                                "GPU$$Adreno (TM) 418"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 420"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 430"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 505"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 506"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 510"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 530"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 540"
                            ]
                        ],                        
                        [
                            [
                                "GPU$$Adreno (TM) 630"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-G71"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T624"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T628"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T720"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T760"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T830"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T860"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T880"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-G72"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR Rogue G6200"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR Rogue G6430"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mesa DRI Intel(R) HD Graphics 515 (Skylake GT2) "
                            ]
                        ],
                        [
                            [
                                "GPU$$Mesa DRI Intel(R) HD Graphics 400 (Braswell) "
                            ]
                        ],
                        [
                            [
                                "MODEL=Nexus 9"
                            ]
                        ]
                    ]
                },
                {
                    "GPU_4" : [
                        [
                            [
                                "GPU$$Intel(R) HD Graphics 4000"
                            ]
                        ],
                        [
                            [
                                "GPU$$Intel(R) HD Graphics Family"
                            ]
                        ],
                        [
                            [
                                "GPU$$Intel(R) HD Graphics for BayTrail"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 330"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 405"
                            ]
                        ],
                        [
                            [
                                "GPU$$NVIDIA Tegra 4"
                            ]
                        ]
                    ]
                },
                {
                    "GPU_3" : [
                        [
                            [
                                "GPU$$PowerVR SGX 544MP2"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 544MP"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 320"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali-T604"
                            ]
                        ]
                    ]
                },
                {
                    "GPU_2" : [
                        [
                            [
                                "GPU$$Adreno (TM) 306"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 544"
                            ]
                        ],                       
                        [
                            [
                                "GPU$$NVIDIA Tegra 3"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali"
                            ],
                            [
                                "GPU$$450"
                            ]
                        ],
                        [
                            [
                                "GPU=PowerVR SGX 543"
                            ]
                        ]
                    ]
                },
                {
                    "GPU_1" : [
                    	[
                            [
                                "GPU$$Vivante GC1000"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 304"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 203"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 205"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 220"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 225"
                            ]
                        ],
                        [
                            [
                                "GPU$$Adreno (TM) 305"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 530"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 531"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 535"
                            ]
                        ],
                        [
                            [
                                "GPU$$PowerVR SGX 540"
                            ]
                        ]
                    ]
                },
                {
                    "GPU_0" : [
                        [
                            [
                                "GPU=Adreno (TM) 200"
                            ]
                        ],
                        [
                            [
                                "GPU$$Mali"
                            ],
                            [
                                "GPU$$400"
                            ]
                        ]
                    ]
                }
            ],
            "overrides" : {
                "GPU_0" : {
                    "GPU_Level" : 0,
                    "HideOptionalDecos" : true,
                    "ShowAllRecommendedCostumesInMilestone" : false,
                    "UseBarla" : false,
                    "UseCurvature" : false,
                    "UseIngameUITextEffect" : false,
                    "UseLinearSpace" : false,
                    "UseLowMaterials" : true,
                    "UseLowModels" : true,
                    "UseLowParticles" : true,
                    "UseSpecularLight" : false,
                    "UseSpecularMask" : false,
                    "UseUIDespicableScoreParticles" : false,
                    "MaxOutline" : 1,
                    "PlatformPriority" : 0,
                    "TextureStartLOD" : 1,
                    "UseShadows" : 0,
                    "BackgroundFarPlane" : 250.0,
                    "DecosAnimationRadius" : 30.0,
                    "DecoGenerationGroupAllowedDecosLerp" : 0.5,
                    "MapCamera_maxVisibilityOffsetFront" : 38.0,
                    "SceneMgrCullingRadius" : 100.0,
                    "SceneMgrCullingDistance" : 170.0,
                    "SceneMgrCullingScreenPixels" : 9.0,
                    "UseEmissiveness" : false,
                    "ForceRoadShader" : false
                },
                "GPU_1" : {
                    "GPU_Level" : 1,
                    "HideOptionalDecos" : true,
                    "ShowAllRecommendedCostumesInMilestone" : false,
                    "UseBarla" : false,
                    "UseCurvature" : false,
                    "UseIngameUITextEffect" : false,
                    "UseLinearSpace" : false,
                    "UseLowMaterials" : true,
                    "UseLowModels" : true,
                    "UseLowParticles" : true,
                    "UseSpecularLight" : false,
                    "UseSpecularMask" : false,
                    "UseUIDespicableScoreParticles" : false,
                    "MaxOutline" : 1,
                    "PlatformPriority" : 0,
                    "UseShadows" : 1,
                    "BackgroundFarPlane" : 250.0,
                    "DecosAnimationRadius" : 50.0,
                    "DecoGenerationGroupAllowedDecosLerp" : 0.6,
                    "MapCamera_maxVisibilityOffsetFront" : 38.0,
                    "SceneMgrCullingRadius" : 100.0,
                    "SceneMgrCullingDistance" : 170.0,
                    "SceneMgrCullingScreenPixels" : 9.0,
                    "UseEmissiveness" : false
                },
                "GPU_2" : {
                    "GPU_Level" : 2,
                    "HideOptionalDecos" : true,
                    "ShowAllRecommendedCostumesInMilestone" : false,
                    "UseBarla" : false,
                    "UseCurvature" : false,
                    "UseLinearSpace" : false,
                    "UseLowMaterials" : true,
                    "UseLowModels" : true,
                    "UseLowParticles" : true,
                    "UseSpecularLight" : false,
                    "UseSpecularMask" : false,
                    "MaxOutline" : 1,
                    "PlatformPriority" : 0,
                    "UseShadows" : 2,
                    "BackgroundFarPlane" : 400.0,
                    "DecosAnimationRadius" : 75.0,
                    "MapCamera_maxVisibilityOffsetFront" : 38.0,
                    "SceneMgrCullingRadius" : 100.0,
                    "SceneMgrCullingDistance" : 170.0,
                    "SceneMgrCullingScreenPixels" : 9.0,
                    "UseEmissiveness" : false
                },
                "GPU_3" : {
                    "HideOptionalDecos" : true,
                    "ShowAllRecommendedCostumesInMilestone" : false,
                    "SynchronizedObjectDistance" : 50.0
                },
                "GPU_4" : {
                    "GPU_Level" : 4,
                    "UseRimLight" : true,
                    "DecosAnimationRadius" : 125.0,
                    "DecoGenerationGroupAllowedDecosLerp" : 0.8,
                    "SynchronizedObjectDistance" : 60.0
                },
                "GPU_5" : {
                    "GPU_Level" : 5,
                    "UseRimLight" : true,
                    "PlatformPriority" : 10,
                    "UseShadows" : 4,
                    "BackgroundFarPlane" : 800.0,
                    "DecosAnimationRadius" : 150.0,
                    "DecoGenerationGroupAllowedDecosLerp" : 1.0,
                    "SynchronizedObjectDistance" : 70.0,
                    "MsaaEnum" : 2
                }
            },
            "priority" : [
                
            ]
        },
        "MEM" : {
            "defaults" : [
                {
                    "Default" : [
                        [
                            "MEM_Level",
                            1,
                            "Mem level",
                            "[0;5]"
                        ],
                        [
                            "TextureBudget",
                            128,
                            "texture budget in MB",
                            "[0;200]"
                        ]
                    ]
                }
            ],
            "selection" : [
                {
                    "MEM_Extreme_low" : [
                        [
                            [
                                "MEM_T<=1024"
                            ]
                        ]
                    ]
                },
                {
                    "MEM_Low" : [
                        [
                            [
                                "MEM_T>1024"
                            ],
                            [
                                "MEM_T<=2048"
                            ]
                        ]
                    ]
                },
                {
                    "MEM_High" : [
                        [
                            [
                                "MEM_T>2048"
                            ]
                        ]
                    ]
                }
            ],
            "overrides" : {
                "MEM_Extreme_low" : {
                    "MEM_Level" : 0,
                    "TextureBudget" : 50
                },
                "MEM_High" : {
                    "MEM_Level" : 2
                },
                "MEM_Low" : {
                    "TextureBudget" : 100
                }
            },
            "priority" : [
                
            ]
        },
        "DLC" : {
            "defaults" : [
                {
                    "Default" : [
                        [
                            "ManhanttanPerformance",
                            2,
                            "0 - Low, 1 - Medium, 2 - High",
                            "[0;2]"
                        ]
                    ]
                }
            ],
            "selection" : [
				{
                    "DLC_high" : [
                        
                    ]
                },
                {
                    "DLC_medium" : [
                        
                    ]
                },
                {
                    "DLC_low" : [
                        
                    ]
                }
            ],
            "overrides" : {
                "DLC_low" : {
                    "ManhanttanPerformance": 0
                },
                "DLC_medium" : {
                    "ManhanttanPerformance": 1
                },
                "DLC_high" : {
                    "ManhanttanPerformance": 2
                }
            },
            "priority" : [
                
            ]
        },
        "Specific" : {
            "defaults" : [
                {
                    "Default" : [
                        
                    ]
                }
            ],
            "selection" : [
                
            ],
            "overrides" : [
                
            ],
            "priority" : [
                
            ]
        }
    }
}
