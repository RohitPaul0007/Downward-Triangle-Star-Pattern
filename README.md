# Downward-Triangle-Star-Pattern in JS
let n = 20;
for (let i = 0; i < n; i++) {
  for (let k = 0; k < n - i; k++) {
    process.stdout.write('*');
  }
  console.log();
}
