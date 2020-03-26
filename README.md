# Firestore-request-response-converter

These APIGEE shared flow' uploadable zip folders.

To use FirebaseRequestConverter:
1. Set your regular JSON to the context variable - "standardInput"
2. Use the shared flow using a Flow Callout policy.
3. Read the output - converted Firestore REST API request JSON specific JSON in the context variable - "firestoreOutput" 

To use FirebaseResponseConverter:
1. Set your Firestore response JSON to the context variable - "firestoreInput"
2. Use the shared flow using a Flow Callout policy.
3. Read the output - converted regular JSON in the context variable - "standardOutput" 
