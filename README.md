# Antidepressant Withdrawal Risk Calculator

A clinical tool for healthcare providers to assess antidepressant withdrawal risk based on published research.

## About

This calculator is based on the research paper by Horowitz, M.A., Framer, A., Hengartner, M.P. et al. "Estimating Risk of Antidepressant Withdrawal from a Review of Published Data" published in CNS Drugs (2023).

## Features

- **Real-time Risk Assessment**: Immediate calculation of withdrawal risk scores
- **Clinical Recommendations**: Evidence-based tapering guidance for each risk level
- **Export Functionality**: Save assessment results for patient records
- **Mobile Responsive**: Optimized for use on tablets and mobile devices
- **Analytics Tracking**: Built-in Vercel Analytics for usage insights

## Risk Stratification

The tool evaluates four key factors:
- Duration of antidepressant use
- Type of antidepressant medication
- Current dosage level
- Past withdrawal experience

## Tapering Recommendations

Based on total risk score:
- **Low Risk (0 points)**: ~50% initial reduction
- **Medium Risk (1-4 points)**: ~25% initial reduction  
- **High Risk (5-8 points)**: ~10% initial reduction
- **Very High Risk (≥9 points)**: ~5% initial reduction (or less)

## Deployment

This is a static web application designed for deployment on Vercel with analytics enabled.

## Reference

Horowitz, M.A., Framer, A., Hengartner, M.P. et al. Estimating Risk of Antidepressant Withdrawal from a Review of Published Data. CNS Drugs 37, 143–157 (2023). https://doi.org/10.1007/s40263-022-00960-y

## Disclaimer

This tool is for healthcare professionals and should be used in conjunction with clinical judgment. It does not replace professional medical advice.
