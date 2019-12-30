# s3-backup-bucket
# Bucket erstellen
1. install nodejs
2. <code>npm i -g serverless</code>
3. clone the repository
4. <code>cd s3-backup-bucket</code>
5. <code>serverless config credentials --provider aws  --key AWS_KEY --secret AWS_SECRET</code>
6. <code>serverless deploy</code>
<h2>Bucket Verwalten mit aws-cli auf Linux</h2>
<ul>
<li>
  <code>curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"</code><br/>
  <code>unzip awscliv2.zip</code> <br/>
  <code>sudo ./aws/install </code>
</li>
<li>
  <code>aws2 configure</code>
</li>
<li><code>aws2 --version</code></li>
<li>
  <p>
  Mit s3 bucket arbeiten <br/>
  <code>aws2 s3 cp file.txt s3://bucket-name/path  // Kopiert File ins s3 bucket </code><br/>
  <code>aws2 s3 mv file.txt s3://bucket-name/path  // Verschiebt File ins s3 bucket</code> <br/>
  <code>aws2 s3 rm s3://bucket-name/path/file.txt  // Entfernt file aus s3 bucket </code>   <br/>
  </p>
  <p>weitere Befehle auf:<br/>
  <a href="https://docs.aws.amazon.com/de_de/cli/latest/userguide/cli-services-s3.html">AWS-CLI s3 Docs</a>
  </p>
</li>
</ul>
   
