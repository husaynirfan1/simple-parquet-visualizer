# Parquet Visualizer 

Simple parquet visualizer using html. Preferrably use artifacts folder to input parquet files, but you could easily browse your parquet files too.

## File Structure

```
artifacts/
├── your-graphrag-file1.parquet
├── your-graphrag-file2.parquet
└── other-parquet-files.parquet
```

## Supported File Types

- **Parquet files** (.parquet): Standard Parquet files from GraphRAG
- **CSV files** (.csv): For testing or when Parquet files are not available

## How It Works

1. Place your Parquet files in this folder
2. Open the visualizer HTML file
3. Use the "Select Parquet Files" button to load your files
4. Explore the interactive graph visualization

## Notes

- The visualizer will automatically attempt to extract node and edge information from your files
- For best results, use Parquet files that follow the GraphRAG schema
- You can combine multiple files to create a comprehensive knowledge graph visualization

## Example Files

If you don't have your own files yet, you can use these example patterns for testing:

- Nodes should have unique IDs and descriptive properties
- Links should define source and target node IDs
- Including type information helps with visual categorization

## Troubleshooting

If your files don't visualize correctly:
- Verify they are valid Parquet/CSV files
- Check for required columns (id, source, target)
- Try a smaller subset of data first

For more assistance, refer to the visualization documentation.
