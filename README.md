# Azure-AI200-AcrKEDA
Lab practice on pushing image into Azure Container Registry and implementing KEDA(Kubernetes Event-driven Autoscaling).

1. Provisioning a secure, serverless Azure Container Apps (ACA) Environment to host the containerized image.
<img width="850" alt="Screenshot From 2026-10-12 21-08-01" src="https://github.com/user-attachments/assets/3d4b70f9-eb72-4710-b7f1-843da2274a67" />
<br><br>

2. Load the environment variables from source code into terminal session.
<img width="1916" height="486" alt="Screenshot From 2026-10-13 09-13-34" src="https://github.com/user-attachments/assets/92273717-641c-42a5-a1a5-ac542a08bdb4" />
<br><br>

3. Following command to update the container app with an HTTP scale rule. This rule monitors concurrent in-flight requests and scales the app when demand increases.
<img width="1907" height="626" alt="Screenshot From 2026-10-13 09-53-17" src="https://github.com/user-attachments/assets/5ea168f8-4f36-459d-8126-0cdc97c02737" />
<br><br>


4. Verify the scale rule is configured.
<img width="1907" height="385" alt="Screenshot From 2026-10-13 09-54-18" src="https://github.com/user-attachments/assets/028602ed-80a3-4d4f-9347-bc3e916081ae" />
<br><br>

5. In terminal, run "python -m venv .venv" to create a virtual environment for the client app.
<br><br>

6. Then, run "source .venv/bin/activate" to activate the Python environment.
<br><br>

7. Once environments is configured, run the client app via command "python app.py"
<img width="1912" height="563" alt="Screenshot From 2026-10-13 10-19-56" src="https://github.com/user-attachments/assets/66152cbb-025c-41c0-99eb-4da5b4fcfdf7" />
<br><br>

8. Client app will hosted at http://127.0.0.1:5000.
<img width="1917" height="930" alt="Screenshot From 2026-10-13 10-20-35" src="https://github.com/user-attachments/assets/5e5ba506-19b7-4c3f-bc6c-ca11aa24ff4d" />
<br><br>

9. Start the session test with 25 concurrency will increase the replicas.
<img width="1917" height="930" alt="Screenshot From 2026-10-13 10-20-35" src="https://github.com/user-attachments/assets/9b170b7c-ed27-4479-80bc-d7e63d683f62" />
<br><br>

10

 



