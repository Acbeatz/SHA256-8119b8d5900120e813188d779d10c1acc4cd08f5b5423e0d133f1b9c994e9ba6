# SHA256-8119b8d5900120e813188d779d10c1acc4cd08f5b5423e0d133f1b9c994e9ba6
SHA256: 8119b8d5900120e813188d779d10c1acc4cd08f5b5423e0d133f1b9c994e9ba6
{
  "human_pretty": "MH8-Acbeatz.com — MH8 Graffiti Mint UI\nReceipt: Archetype Mint (dual-layer)\nArchetype: MH8=LOVE=>8<=<8>=(0)\nLogic: MY SONG HERE\nTimestamp: 2025-12-26T15:22:42.240Z\nSHA256: 699d40d5fc3c31ed283f8d5bacc1d11864dc55e9003dc1f6264bda7cd0b36e28\nBrand: MH8-Acbeatz.com\nCrypto receipt: ✅ Complete (local SHA-256)\nCourt / audit / dispute: ✅ Strong baseline (pair with artifact)\nIntegrity rule: NON-COPIABLE WHEN HASH-CHAIN BROKEN\n© 2026 MH8-Graffiti by Acbeatz.com — All rights reserved.",
  "machine_hard": {
    "mh8_system": "MH8-Acbeatz.com",
    "brand": "MH8-Acbeatz.com",
    "created_utc": "2025-12-26T15:22:42.240Z",
    "integrity_rule": "NON-COPIABLE WHEN HASH-CHAIN BROKEN",
    "core_payload": {
      "mh8_system": "MH8-GRAFFITI",
      "receipt_type": "MH8-GRAFFITI-ARCHETYPE-MINT",
      "receipt_version": "GRAFFITI_UI_V7.4",
      "created_utc": "2025-12-26T15:22:42.240Z",
      "artifact": {
        "archetype": "MH8=LOVE=>8<=<8>=(0)",
        "logic": [
          "MY",
          "SONG",
          "HERE"
        ],
        "badge": null
      }
    },
    "hash_input": "MH8-Acbeatz.com|{\"artifact\":{\"archetype\":\"MH8=LOVE=>8<=<8>=(0)\",\"badge\":null,\"logic\":[\"MY\",\"SONG\",\"HERE\"]},\"created_utc\":\"2025-12-26T15:22:42.240Z\",\"mh8_system\":\"MH8-GRAFFITI\",\"receipt_type\":\"MH8-GRAFFITI-ARCHETYPE-MINT\",\"receipt_version\":\"GRAFFITI_UI_V7.4\"}",
    "hash_input_stats": {
      "hash_input_bytes": 258,
      "LF": 0,
      "CRLF": 0,
      "CR": 0,
      "endsWithNewline": "NO",
      "preview_first_80": "MH8-Acbeatz.com|{\"artifact\":{\"archetype\":\"MH8=LOVE=>8<=<8>=(0)\",\"badge\":null,\"lo",
      "preview_last_80": "eceipt_type\":\"MH8-GRAFFITI-ARCHETYPE-MINT\",\"receipt_version\":\"GRAFFITI_UI_V7.4\"}"
    },
    "sha256_hex": "699d40d5fc3c31ed283f8d5bacc1d11864dc55e9003dc1f6264bda7cd0b36e28",
    "cryptographic_receipt_status": "VERIFIED_LOCAL",
    "court_audit_dispute_evidence_status": "COMPLETE_FOR_BASIC_DISPUTE",
    "reproducible_hashing_instructions": [
      "1) Rebuild core_payload exactly (same keys/values).",
      "2) Canonicalize core_payload as stableStringify (sorted keys, no whitespace).",
      "3) Build hash_input = brand + '|' + canonical_core_payload.",
      "4) SHA-256 over UTF-8 bytes of hash_input => sha256_hex.",
      "5) Compare computed sha256_hex to this receipt's sha256_hex."
    ],
    "sealing_metadata": {
      "sealed_by": "MH8-Graffiti Mint UI (client-side)",
      "sealing_mode": "SELF_SEALED_LOCAL_SHA256",
      "note": "Keep the exported receipt + associated artifact for provenance."
    }
  }
}
