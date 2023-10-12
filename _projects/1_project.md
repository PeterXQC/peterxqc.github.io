---
layout: page
title: project 1
description: test
img: assets/img/12.jpg
importance: 1
category: work
related_publications:
---

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Interactive Plot</title>
</head>
<body>


<!-- Load require.js. Delete this if your page already loads require.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.4/require.min.js" integrity="sha256-Ae2Vz/4ePdIu6ZyI/5ZGsYnb+m0JlOmKPjt6XZ9JJkA=" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/@jupyter-widgets/html-manager@^1.0.1/dist/embed-amd.js" crossorigin="anonymous"></script>

<script type="application/vnd.jupyter.widget-state+json">
{
  "version_major": 2,
  "version_minor": 0,
  "state": {
    "da4b324c499d445f9a9b9cebb2189d69": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "0e5ab798647a463dbf06d97f0b90dad6": {
      "model_name": "SliderStyleModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "15a8290cf0fd47afb57fd26189a889a7": {
      "model_name": "FloatSliderModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [],
        "description": "r:",
        "layout": "IPY_MODEL_da4b324c499d445f9a9b9cebb2189d69",
        "max": 4.0,
        "step": 0.01,
        "style": "IPY_MODEL_0e5ab798647a463dbf06d97f0b90dad6",
        "value": 1.87
      }
    },
    "8c46c0a2009b461b936f5a03a5db9000": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "77d133004e0d4127a76e10683566ecc6": {
      "model_name": "SliderStyleModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "ef3da7c47e6a4a939281ee82f18d9e3e": {
      "model_name": "FloatSliderModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [],
        "description": "x_0:",
        "layout": "IPY_MODEL_8c46c0a2009b461b936f5a03a5db9000",
        "max": 1.0,
        "step": 0.01,
        "style": "IPY_MODEL_77d133004e0d4127a76e10683566ecc6",
        "value": 0.5
      }
    },
    "aac0b27c59374320b6d4598a165a54f7": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "a4cfb18230984485834219fb54099eb5": {
      "model_name": "SliderStyleModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "8c34a69458e74583a8f87f91d3f100ab": {
      "model_name": "IntSliderModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [],
        "description": "depth:",
        "layout": "IPY_MODEL_aac0b27c59374320b6d4598a165a54f7",
        "max": 5,
        "min": 1,
        "style": "IPY_MODEL_a4cfb18230984485834219fb54099eb5",
        "value": 2
      }
    },
    "2814360c682b4fad8cf95dffc78e1ea8": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "8d772f988fee4649af27eda1706950fb": {
      "model_name": "SliderStyleModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "b463cb4cd75b40888126db413ef4ee9d": {
      "model_name": "IntSliderModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [],
        "description": "#iter:",
        "layout": "IPY_MODEL_2814360c682b4fad8cf95dffc78e1ea8",
        "min": 1,
        "style": "IPY_MODEL_8d772f988fee4649af27eda1706950fb",
        "value": 25
      }
    },
    "593ede52603b4a23ac9ea25d38faa353": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "61fbb42f03e343b7a96a0de0be2012e2": {
      "model_name": "TextStyleModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "45d74cf721244483bfd060829eec18c7": {
      "model_name": "TextModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [],
        "description": "Function:",
        "layout": "IPY_MODEL_593ede52603b4a23ac9ea25d38faa353",
        "placeholder": "Enter a function with variables x and r",
        "style": "IPY_MODEL_61fbb42f03e343b7a96a0de0be2012e2",
        "value": "r * x * (1 - x)"
      }
    },
    "80a8d44244e94a8aacd4bd1d8fd92ebd": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {
        "height": "600px"
      }
    },
    "6e688944122842fa9324a0edac17ca9b": {
      "model_name": "VBoxModel",
      "model_module": "@jupyter-widgets/controls",
      "model_module_version": "2.0.0",
      "state": {
        "_dom_classes": [
          "widget-interact"
        ],
        "children": [
          "IPY_MODEL_45d74cf721244483bfd060829eec18c7",
          "IPY_MODEL_8c34a69458e74583a8f87f91d3f100ab",
          "IPY_MODEL_15a8290cf0fd47afb57fd26189a889a7",
          "IPY_MODEL_ef3da7c47e6a4a939281ee82f18d9e3e",
          "IPY_MODEL_b463cb4cd75b40888126db413ef4ee9d",
          "IPY_MODEL_5abb77c266244e6c8571a39d35147851"
        ],
        "layout": "IPY_MODEL_80a8d44244e94a8aacd4bd1d8fd92ebd"
      }
    },
    "c354143fe26a43579ccdb8908a169d31": {
      "model_name": "LayoutModel",
      "model_module": "@jupyter-widgets/base",
      "model_module_version": "2.0.0",
      "state": {}
    },
    "5abb77c266244e6c8571a39d35147851": {
      "model_name": "OutputModel",
      "model_module": "@jupyter-widgets/output",
      "model_module_version": "1.0.0",
      "state": {
        "_dom_classes": [],
        "layout": "IPY_MODEL_c354143fe26a43579ccdb8908a169d31",
        "outputs": [
          {
            "output_type": "display_data",
            "data": {
              "text/plain": "<Figure size 640x480 with 1 Axes>",
              "image/png": "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"
            },
            "metadata": {}
          }
        ]
      }
    }
  }
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{"version_major": 2, "version_minor": 0, "model_id": "6e688944122842fa9324a0edac17ca9b"}
</script>

</body>
</html>

```
{% endraw %}
