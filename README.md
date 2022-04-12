# How to write CDK Outputs to a File

A repository for an article on
[bobbyhadz.com](https://bobbyhadz.com/blog/aws-cdk-outputs-file)

## How to Use

1. Clone the repository

2. Install the dependencies

```bash
npm install
```

3. Create the CDK stack

```bash
npx aws-cdk deploy cdk-stack \
  --outputs-file ./cdk-outputs.json
```

4. Once you deploy, a file named `cdk-outputs.json` will be created in the root
   directory of your CDK project.

5. Cleanup

```bash
npx aws-cdk destroy
```
