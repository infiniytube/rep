{
	"approved" : true,
	"contentrating" : "Everyone",
	"description" : "NieR: Automata wallpaper featuring various characters from the game.\r\n\r\nFor auto-scaling to work correctly, set the alignment to center.\r\n\r\nFeatures:\r\n- Adaptive to different resolutions\r\n- Customizable aspect ratio\r\n- Audio visualizer\r\n- Title and cover of currently playing media\r\n- Time\r\n- Date\r\n- Two versions of the art\r\n- A lot of options to change\r\n\r\nThis wallpaper is a collaborative work by Novaturion and myself.\r\nOriginal artwork by eggloaf.",
	"file" : "scene.json",
	"general" : 
	{
		"properties" : 
		{
			"_24hrformat" : 
			{
				"condition" : "clock.value == true && time.value == true",
				"index" : 11,
				"order" : 111,
				"text" : "24hr format",
				"type" : "bool",
				"value" : false
			},
			"ampm" : 
			{
				"condition" : "clock.value == true && time.value == true && _24hrformat.value == false",
				"index" : 12,
				"order" : 112,
				"text" : "AM/PM",
				"type" : "bool",
				"value" : true
			},
			"art" : 
			{
				"index" : 16,
				"options" : 
				[
					{
						"label" : "None",
						"value" : "none"
					},
					{
						"label" : "Default",
						"value" : "default"
					},
					{
						"label" : "No Characters",
						"value" : "no-characters"
					}
				],
				"order" : 116,
				"text" : "Art",
				"type" : "combo",
				"value" : "default"
			},
			"aspectratio" : 
			{
				"index" : 0,
				"options" : 
				[
					{
						"label" : "Screen",
						"value" : "0"
					},
					{
						"label" : "4:3",
						"value" : "1.333333"
					},
					{
						"label" : "16:9",
						"value" : "1.777777"
					},
					{
						"label" : "16:10",
						"value" : "1.6"
					},
					{
						"label" : "21:9",
						"value" : "2.333333"
					},
					{
						"label" : "32:9",
						"value" : "3.555555"
					}
				],
				"order" : 100,
				"text" : "Aspect Ratio",
				"type" : "combo",
				"value" : "0"
			},
			"audiovisualizer" : 
			{
				"index" : 19,
				"order" : 119,
				"text" : "Audio Visualizer",
				"type" : "bool",
				"value" : true
			},
			"audiovisualizerbars" : 
			{
				"condition" : "audiovisualizer.value == true",
				"fraction" : false,
				"index" : 20,
				"max" : 200,
				"min" : 1,
				"order" : 120,
				"text" : "Audio Visualizer Bars",
				"type" : "slider",
				"value" : 20
			},
			"chromaticabberation" : 
			{
				"index" : 29,
				"order" : 129,
				"text" : "Chromatic Abberation",
				"type" : "bool",
				"value" : true
			},
			"chromaticabberationstrength" : 
			{
				"condition" : "chromaticabberation.value == true",
				"fraction" : true,
				"index" : 30,
				"max" : 2,
				"min" : 0,
				"order" : 130,
				"precision" : 3,
				"step" : 0.01,
				"text" : "Chromatic Abberation Strength",
				"type" : "slider",
				"value" : 0.15
			},
			"clock" : 
			{
				"index" : 4,
				"order" : 104,
				"text" : "Clock",
				"type" : "bool",
				"value" : true
			},
			"date" : 
			{
				"condition" : "clock.value == true",
				"index" : 13,
				"order" : 113,
				"text" : "Date",
				"type" : "bool",
				"value" : true
			},
			"datebar" : 
			{
				"condition" : "clock.value == true",
				"index" : 14,
				"order" : 114,
				"text" : "Date Bar",
				"type" : "bool",
				"value" : true
			},
			"lefttoplines" : 
			{
				"index" : 17,
				"order" : 117,
				"text" : "Left Top Lines",
				"type" : "bool",
				"value" : true
			},
			"mediacover" : 
			{
				"index" : 23,
				"order" : 123,
				"text" : "Media Cover",
				"type" : "bool",
				"value" : true
			},
			"medianame" : 
			{
				"condition" : "",
				"index" : 21,
				"order" : 121,
				"text" : "Media Name",
				"type" : "bool",
				"value" : true
			},
			"medianameshadow" : 
			{
				"condition" : "",
				"index" : 22,
				"order" : 122,
				"text" : "Media Name Shadow",
				"type" : "bool",
				"value" : true
			},
			"particles" : 
			{
				"index" : 24,
				"order" : 124,
				"text" : "Particles",
				"type" : "bool",
				"value" : true
			},
			"particlescount" : 
			{
				"condition" : "particles.value == true",
				"fraction" : true,
				"index" : 27,
				"max" : 2,
				"min" : 0.01,
				"order" : 127,
				"precision" : 3,
				"step" : 0.01,
				"text" : "Particles Count",
				"type" : "slider",
				"value" : 1
			},
			"particleslifetime" : 
			{
				"condition" : "particles.value == true",
				"fraction" : true,
				"index" : 28,
				"max" : 2,
				"min" : 0.01,
				"order" : 128,
				"precision" : 3,
				"step" : 0.01,
				"text" : "Particles Lifetime",
				"type" : "slider",
				"value" : 1
			},
			"particlessize" : 
			{
				"condition" : "particles.value == true",
				"fraction" : true,
				"index" : 26,
				"max" : 2,
				"min" : 0.01,
				"order" : 126,
				"precision" : 3,
				"step" : 0.01,
				"text" : "Particles Size",
				"type" : "slider",
				"value" : 1
			},
			"particlesspeed" : 
			{
				"condition" : "particles.value == true",
				"fraction" : true,
				"index" : 25,
				"max" : 2,
				"min" : 0.01,
				"order" : 125,
				"precision" : 3,
				"step" : 0.01,
				"text" : "Particles Speed",
				"type" : "slider",
				"value" : 1
			},
			"pointer" : 
			{
				"condition" : "clock.value == true",
				"index" : 5,
				"order" : 105,
				"text" : "Pointer",
				"type" : "bool",
				"value" : true
			},
			"rightbottomlines" : 
			{
				"index" : 18,
				"order" : 118,
				"text" : "Right Bottom Lines",
				"type" : "bool",
				"value" : true
			},
			"schemecolor" : 
			{
				"order" : 0,
				"text" : "ui_browse_properties_scheme_color",
				"type" : "color",
				"value" : "0.6745098039215687 0.6470588235294118 0.5764705882352941"
			},
			"seconds" : 
			{
				"condition" : "clock.value == true && time.value == true",
				"index" : 10,
				"order" : 110,
				"text" : "Seconds",
				"type" : "bool",
				"value" : true
			},
			"showday" : 
			{
				"condition" : "clock.value == true && date.value == true",
				"index" : 15,
				"order" : 115,
				"text" : "Show Day",
				"type" : "bool",
				"value" : true
			},
			"text" : 
			{
				"index" : 1,
				"order" : 101,
				"text" : "Text",
				"type" : "bool",
				"value" : true
			},
			"textshadow" : 
			{
				"condition" : "",
				"index" : 2,
				"order" : 102,
				"text" : "Text Shadow",
				"type" : "bool",
				"value" : true
			},
			"textvalue" : 
			{
				"condition" : "text.value == true",
				"index" : 3,
				"order" : 103,
				"text" : "Text Value",
				"type" : "textinput",
				"value" : "TODAY"
			},
			"time" : 
			{
				"condition" : "clock.value == true",
				"index" : 6,
				"order" : 106,
				"text" : "Time",
				"type" : "bool",
				"value" : true
			},
			"timebar" : 
			{
				"condition" : "clock.value == true",
				"index" : 7,
				"order" : 107,
				"text" : "Time Bar",
				"type" : "bool",
				"value" : true
			},
			"timebarblinking" : 
			{
				"condition" : "timebar.value == true",
				"index" : 8,
				"order" : 108,
				"text" : "Time Bar Blinking",
				"type" : "bool",
				"value" : true
			},
			"timebarlines" : 
			{
				"condition" : "clock.value == true",
				"index" : 9,
				"order" : 109,
				"text" : "Time Bar Lines",
				"type" : "bool",
				"value" : true
			}
		},
		"supportsaudioprocessing" : true,
		"supportsvideo" : true,
		"supportsvideoflags" : 2
	},
	"preview" : "preview.gif",
	"ratingsex" : "none",
	"ratingviolence" : "none",
	"tags" : [ "Game" ],
	"title" : "NieR: Automata | Android Machine Robot | eggloaf",
	"type" : "Scene",
	"version" : 14,
	"visibility" : "public",
	"workshopid" : "3002120692",
	"workshopurl" : "steam://url/CommunityFilePage/3002120692"
}
