# Weather Satellite Computer Vision Project

## Simple Scope

Processing and analyzing weather satellite imagery from Meteor-M passes over Minneapolis-St. Paul.

## What This Does

Takes raw satellite images and identifies weather features:

- Cloud formations and types
- Storm systems
- Atmospheric patterns over time
- Regional weather tracking

## Why This Works

- **Unlimited sample data**: Every satellite pass generates new images
- **Clear success criteria**: Recognizable Earth features and cloud patterns
- **Builds on existing work**: Uses the RTL-SDR hardware you’re setting up
- **Practical learning**: Real computer vision work with immediate visual feedback

## The Flow

1. Receive Meteor-M satellite imagery (hardware setup this weekend)
1. Process raw image data into usable format
1. Apply CV techniques to identify features
1. Classify cloud types and weather patterns
1. Track changes across multiple passes

## Technical Learning Goals

- Image processing fundamentals
- Feature detection and classification
- Pattern recognition in noisy data
- Working with multi-spectral satellite imagery
- Time-series analysis of weather patterns

## Initial Implementation Ideas

Start simple:

- Basic image enhancement and contrast adjustment
- Land/water/cloud segmentation
- Cloud classification (cumulus, cirrus, stratus)
- Storm system identification
- Multi-pass comparison

## Notes

This pairs well with HAM radio study - both involve RF reception and signal processing. The CV work can wait until after satellite receiver is operational and you’re collecting actual image data.

Keep this project “on rails” like Vision Command - constrained to weather analysis rather than trying to do all possible satellite image processing.

