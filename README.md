# Next.js Trace Viewer

## Usage

1. run next dev on your nextjs project
2. go to `.next` folder, there you will find the trace files (`.next/trace`)
3. copy the trace file to this directory
4. run the `start` script

   ```bash
   npm start <trace-file>
   ```

   ```bash
   # Add where the trace file exist
   npm start ./trace
   ```

   ```bash
   # You can print the trace to a file
   npm start ./trace > trace.txt
   ```
