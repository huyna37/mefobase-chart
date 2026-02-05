helm dependency update .\CSDL
helm upgrade --install mefobase-csdl .\CSDL --namespace test-namespace --create-namespace
