# Ecru
Resume Best Match Project
1. Run all cells in .ipynb file at once.
2. Go to last cell and get the Gloable link.
3. Make API call using this lik ex- https://c8de-34-70-189-202.ngrok-free.app/get_resumes_list
4. POST data similar to -
5. {
   "context": "Mortage banking",
   "category": "job",
   "threshold": 0.7,
   "noOfMatches": 3,
   "inputPath": "https://console.cloud.google.com/storage/browser/hackathontestdata2024"
}
6. It will return you result like this-
7. {
    "count": 3,
    "metadata": {
        "confidenceScore": 6.5
    },
    "results": [
        {
            "id": 1,
            "path": "10070224.pdf",
            "score": 6.5
        },
        {
            "id": 2,
            "path": "10001727.pdf",
             "score": 4.7
        },
        {
            "id": 3,
            "path": "10062724.pdf",
            "score": 4.69
        }
    ],
    "status": "success"
}
