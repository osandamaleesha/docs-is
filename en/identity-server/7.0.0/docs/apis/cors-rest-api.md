---
template: templates/redoc.html
---

# CORS API definition

??? Note "Click for instructions"
    Follow the steps given below to try out the REST APIs with your local instance of WSO2 Identity Server 
    (WSO2 IS).

    1.  Click **Authorize** and provide the desired values for authentication.
    2.  Expand the relevant API operation and click the **Try it Out** button.
    3.  Fill in relevant sample values for the input parameters and click **Execute**.
        You will receive a sample curl command with the sample values you filled in.
    4. Add a `-k` header to the curl command and run the curl command on the terminal with a running instance of WSO2 IS.

<redoc spec-url={{base_path}}/apis/restapis/cors.yaml></redoc>
<script src="https://cdn.jsdelivr.net/npm/redoc@next/bundles/redoc.standalone.js"> </script>