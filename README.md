// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

/**
 * @title UnemployCoin (UNEMP)
 * @dev ERC-20 Token with Ownable and Pausable functionality.
 *      This contract implements a standard ERC-20 token with:
 *      - Minting of 1 billion tokens to the deployer upon deployment.
 *      - Ownership control allowing transfer and renounce ownership.
 *      - Pause and unpause functionality to halt token transfers in emergencies.
 *      - Safe allowance and transfer logic following the ERC-20 standard.
 * 
 * Designed to support the UnemployCoin project, aimed at community support.
 * 
 * Features:
 * - ERC-20 compliance with standard functions and events.
 * - Ownable: only owner can perform sensitive actions like pause/unpause.
 * - Pausable: owner can pause all token transfers if needed.
 * 
 * Author: Your Name or Organization
 * Date: 2025-06-04
 */
